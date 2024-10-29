# 📊 Análise e Predição da Expectativa de Vida e Diagnóstico de Câncer de Mama 🌍🩺

Bem-vindo(a) a este projeto de análise de dados e predição! Neste repositório, você encontrará duas abordagens principais: uma para prever a expectativa de vida e outra para diagnosticar câncer de mama com base em dados clínicos.

## 💻 Visão Geral

O projeto utiliza Python e diversas bibliotecas de Machine Learning para análise e modelagem de dois conjuntos de dados distintos:

Diagnóstico de Câncer de Mama: Modelo para classificar como benigno ou maligno com base em características tumorais.
Expectativa de Vida Global: Modelo para prever a expectativa de vida a partir de variáveis demográficas e de saúde.

## 📁 Estrutura do Projeto

O Jupyter Notebook está organizado da seguinte forma:

### 1. Diagnóstico de Câncer de Mama 🩺
Conjunto de Dados: Com o famoso Wisconsin Breast Cancer Dataset, que inclui características de tumores (como textura e simetria) e o diagnóstico como benigno ou maligno.
Pré-processamento e Codificação: Convertendo a variável de diagnóstico em valores numéricos (Benigno -> 0, Maligno -> 1) e padronizando as características para otimizar o treinamento.
Modelagem com Random Forest: Usamos um classificador Random Forest para prever se um tumor é benigno ou maligno.
Avaliação do Modelo: Utilizamos acurácia e relatório de classificação para avaliar o desempenho do modelo.

### 2. Análise da Expectativa de Vida 🌍
Conjunto de Dados: Utilizamos um dataset de expectativa de vida, contendo variáveis relacionadas à saúde e economia em diversos países.
Limpeza e Pré-processamento: Removemos colunas irrelevantes e valores ausentes, tratamos variáveis categóricas e aplicamos padronização para melhorar o desempenho do modelo.
Amostragem e Redução de Dados: Reduzimos o tamanho do conjunto de dados para 10% para realizar experimentos rápidos e leves com o modelo.
Modelagem Preditiva com Random Forest e XGBoost: Testamos ambos os algoritmos para prever a expectativa de vida. Avaliamos com MAE e RMSE para medir a precisão das previsões.
Configuração Simplificada do XGBoost: Criamos uma versão minimalista do modelo XGBoost para ajustar a modelos leves em dados menores.

## 🚀 Como Usar

Para executar este notebook:
1. **Clone este repositório:**
   ```bash
   git clone https://github.com/renatovcs/ml-cancer-expecvida

2. **Certifique-se de ter pandas, sklearn, e xgboost instalados.**

3. **Execute o Notebook:** Abra o Jupyter Notebook e execute cada célula para ver as análises e os resultados dos modelos preditivos.

## 📊 Resultados e Métricas

Para o modelo de câncer de mama, foi utilizada a acurácia como principal métrica.
Para o modelo de expectativa de vida, MAE e RMSE.

## ✨ Contribuições

Contribuições são bem-vindas! Abra uma issue ou envie um pull request para discutir novas ideias.
