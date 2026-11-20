# Data Visualization in Python (freeCodeCamp)

Soluções em Jupyter Notebook dos projetos do curso **Data Analysis with Python** da [freeCodeCamp](https://www.freecodecamp.org/): análise e visualização de dados com Python, pandas, NumPy, matplotlib e seaborn. Cada notebook tem um badge para abrir direto no Google Colab.

## Notebooks

| Notebook | O que faz | Bibliotecas |
| :--- | :--- | :--- |
| `boilerplate_demographic_data_analyzer.ipynb` | Analisador de dados demográficos: contagem por raça, idade média, percentuais por escolaridade e renda a partir de `adult.data.csv`. | pandas |
| `boilerplate_mean_variance_std_freecodecamp.ipynb` | Recebe 9 números, monta uma matriz 3x3 e calcula média, variância, desvio padrão, máximo, mínimo e soma por eixo. | NumPy |
| `boilerplate_page_views_time_series_visualizer.ipynb` | Visualizador de séries temporais das visitas diárias ao fórum da freeCodeCamp (`fcc-forum-pageviews.csv`), com limpeza de outliers por quantis e gráficos de linha. | pandas, matplotlib, seaborn |
| `boilerplate_sea_level_predictor.ipynb` | Preditor do nível do mar: gráfico de dispersão (`epa-sea-level.csv`) e retas de regressão linear projetadas até 2050. | pandas, matplotlib, SciPy (`linregress`), NumPy |
| `bolierplate_medica_data_visualizer.ipynb` | Visualizador de dados médicos (`medical_examination.csv`): coluna de sobrepeso, normalização de colesterol e glicose, gráfico categórico e matriz de correlação. | pandas, seaborn, matplotlib, NumPy |

## Como rodar

Pelo Colab, use o badge no topo de cada notebook, ou localmente:

```bash
gh repo clone voaneves/Data-Visualization-in-Python-freeCodeCamp
cd Data-Visualization-in-Python-freeCodeCamp
pip install pandas numpy matplotlib seaborn scipy jupyter
jupyter notebook
```

Os arquivos CSV usados (`adult.data.csv`, `fcc-forum-pageviews.csv`, `epa-sea-level.csv`, `medical_examination.csv`) não estão neste repositório; baixe-os dos projetos de boilerplate da freeCodeCamp e coloque na mesma pasta do notebook.

## Aprendizados

Manipulação e limpeza de dados com pandas, operações vetorizadas com NumPy, regressão linear com SciPy e gráficos estatísticos com matplotlib e seaborn.

## License

A licença MIT em [LICENSE](LICENSE) cobre apenas as soluções do autor. Os enunciados dos projetos e o código base (boilerplate) vêm da certificação "Data Analysis with Python" da freeCodeCamp; os repositórios originais do boilerplate não declaram licença, e todos os direitos desse material permanecem com a freeCodeCamp.
