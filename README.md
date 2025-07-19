<!-- Simulação de abas usando detalhes -->
<details open>
<summary>🇧🇷 Português</summary>

# Artigo Científico – Emulação de Projeções Climáticas com ML

Este repositório contém o conjunto de dados sintético e os códigos-fonte utilizados nas análises apresentadas no artigo científico **"Emulação de Projeções Climáticas via Modelos de Regressão: Uma Análise Preditiva em uma Base de Dados Sintética Fundamentada em Estudos Hidrológicos da Bacia do Rio Grande"**.

## Conteúdo

- 📁 `data/` — Contém o conjunto de dados sintético (`base_sintetica_balanco_hidrico_rio_grande.xlsx`) com 280.000 registros, gerado para replicar a variabilidade estatística das projeções hidrológicas.
- 📁 `notebooks/` — Notebooks Jupyter (`.ipynb`) detalhando cada etapa do processo:
    - `01_data_generation.ipynb`: Geração do conjunto de dados sintético.
    - `02_model_benchmark.ipynb`: Treinamento, avaliação e comparação dos 14 modelos de regressão.
    - `03_exploratory_analysis.ipynb`: Análise exploratória e geração dos gráficos de correlação.
- 📁 `figures/` — Gráficos e diagramas produzidos durante o estudo, incluindo os benchmarks de R² e a análise de importância das variáveis.
- 📄 `results/` — Métricas de desempenho detalhadas para cada modelo em formato CSV ou JSON.

## Objetivo

Este repositório visa garantir a **reprodutibilidade completa** dos experimentos descritos no artigo. Ele permite que outros pesquisadores validem os resultados, explorem os modelos treinados ou adaptem a metodologia para emular projeções climáticas em outras bacias hidrográficas ou contextos.

## Como Citar

Se você utilizar o código ou os dados deste repositório em seu trabalho, por favor cite o artigo original (a referência completa será adicionada após a publicação).

## Observações

- Todos os dados são **sintéticos**, gerados com base nos parâmetros estatísticos e nos padrões espaciais descritos no estudo hidrológico de referência [Paula, 2019].
- As dependências de bibliotecas Python necessárias para executar os notebooks estão listadas no arquivo `requirements.txt`.

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).

</details>

<details>
<summary>🇺🇸 English</summary>

# Scientific Article – ML-based Emulation of Climate Projections

This repository contains the synthetic dataset and source code used in the analyses presented in the scientific article **"Emulation of Climate Projections via Regression Models: A Predictive Analysis on a Synthetic Dataset Grounded in Hydrological Studies of the Rio Grande Basin"**.

## Contents

- 📁 `data/` — Contains the synthetic dataset (`base_sintetica_balanco_hidrico_rio_grande.xlsx`) with 280,000 records, generated to replicate the statistical variability of hydrological projections.
- 📁 `notebooks/` — Jupyter notebooks (`.ipynb`) detailing each step of the process:
    - `01_data_generation.ipynb`: Generation of the synthetic dataset.
    - `02_model_benchmark.ipynb`: Training, evaluation, and comparison of the 14 regression models.
    - `03_exploratory_analysis.ipynb`: Exploratory analysis and generation of correlation plots.
- 📁 `figures/` — Plots and diagrams produced during the study, including R² benchmarks and feature importance analysis.
- 📄 `results/` — Detailed performance metrics for each model in CSV or JSON format.

## Purpose

This repository aims to ensure **full reproducibility** of the experiments described in the article. It allows other researchers to validate the findings, explore the trained models, or adapt the methodology to emulate climate projections in other river basins or contexts.

## How to Cite

If you use the code or data from this repository in your work, please cite the original article (full citation will be added upon publication).

## Notes

- All data are **synthetic**, generated based on the statistical parameters and spatial patterns described in the reference hydrological study [Paula, 2019].
- The Python library dependencies required to run the notebooks are listed in the `requirements.txt` file.

## License

This project is licensed under the [MIT License](LICENSE).

</details>
