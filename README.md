# NO2toTIF 🌫️➡️🗺️

> Transformando arquivos atmosféricos em imagens, porque nem só de ar vive o cientista! 😄

## O que é isso? 🤔

Este repositório contém um notebook (.ipynb) que faz o seguinte:
- Abre um arquivo SurfaceNO2.nc (sim, aquele grandão, cheio de dados atmosféricos de dióxido de nitrogênio! 🧪)
- Recorta a área de interesse (você escolhe, sem complicação! ✂️)
- Salva o resultado bonitinho no formato .tif, pronto para análise, mapas, ou aquela figurinha marota no relatório 🖼️

## Por quê? 🤷

Porque ninguém merece sofrer para converter dados do NetCDF (.nc) para GeoTIFF (.tif)!  
Se você já ficou horas xingando o computador, esse repositório é pra você. 🥲

## Como usar? 🚀

1. **Clone este repositório**  
   ```bash
   git clone https://github.com/seu-usuario/NO2toTIF.git
   ```
2. **Instale as dependências**  
   Recomendo criar um ambiente virtual:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # Linux/Mac
   .venv\Scripts\activate     # Windows
   pip install -r requirements.txt
   ```
   Ou instale direto no Jupyter Notebook usando:
   ```python
   !pip install netCDF4 rasterio numpy matplotlib
   ```

3. **Abra o notebook**  
   ```bash
   jupyter notebook
   ```
   E execute o arquivo `NO2toTIF.ipynb`.

4. **Siga as instruções no notebook!**  
   - Escolha o arquivo .nc 📂
   - Defina sua área de interesse (por coordenadas) 🌍
   - Execute as células e... voilá! Seu .tif estará salvo 🎉

## Requisitos 📋

- Python 3.8+
- [netCDF4](https://unidata.github.io/netcdf4-python/)
- [rasterio](https://rasterio.readthedocs.io/)
- numpy
- matplotlib (opcional, só pra visualizar e se gabar)

## Exemplo de uso 💡

```python
from netCDF4 import Dataset
import rasterio
import numpy as np

# Seu código maravilhoso vai aqui!
```

## Contribua! ✨

Achou um bug? Quer adicionar um novo filtro, sabor ou cor?  
Mande um PR, abra uma issue ou envie um emoji de agradecimento. Toda ajuda é bem-vinda! 🤗

## Licença 📄

MIT, porque compartilhar conhecimento é o que move a ciência (e salvar tempo também!).

---

> 💡 Dica de ouro: respirar fundo antes de rodar o notebook resolve 90% dos problemas. Para os outros 10%, existe o StackOverflow. 😅
