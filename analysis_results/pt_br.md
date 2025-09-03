# Análise de Sobrevivência no Titanic

[![Python 3.8+](https://img.shields.io/badge/Python-3.8%252B-blue)](https://www.python.org/) [![Pandas 1.3+](https://img.shields.io/badge/Pandas-1.3%252B-orange)](https://pandas.pydata.org/) [![Visualização - Seaborn](https://img.shields.io/badge/Visualiza%C3%A7%C3%A3o-Seaborn-green)](https://seaborn.pydata.org/) [![Notebook - Jupyter](https://img.shields.io/badge/Notebook-Jupyter-red)](https://jupyter.org/)

## 📊 Visão Geral do Projeto

Análise exploratória de dados (EDA) completa do dataset do Titanic, investigando os fatores que influenciaram as chances de sobrevivência dos passageiros. Este projeto demonstra habilidades em manipulação de dados, visualização e análise estatística usando Python.

## 📈 Principais Descobertas

1. **Distribuição de Sobrevivência**

    - Apenas 38.4% dos passageiros sobreviveram ao desastre
    - 61.6% dos passageiros não sobreviveram

2. **Classe Social Influenciou Significativamente a Sobrevivência**

    - **1ª classe:** 62.96% de taxa de sobrevivência
    - **2ª classe:** 47.28% de taxa de sobrevivência
    - **3ª classe:** Apenas 24.24% de taxa de sobrevivência

3. **Gênero foi um Fator Determinante**

    - **Mulheres:** 74.20% de taxa de sobrevivência
    - **Homens:** Apenas 18.89% de taxa de sobrevivência

4. **Análise de Correlação**

    - A variável "adult_male" teve a maior correlação negativa com sobrevivência (-0.56)
    - A tarifa ("fare") teve correlação positiva moderada (0.26)
    - A classe ("pclass") teve correlação negativa significativa (-0.34)

5. **Interação entre Classe e Gênero**
   **Mulheres na 1ª classe:** 96.81% de sobrevivência
   **Mulheres na 2ª classe:** 92.11% de sobrevivência
   **Mulheres na 3ª classe:** 50.00% de sobrevivência

    **Homens na 1ª classe:** 36.89% de sobrevivência
    **Homens na 2ª classe:** 15.74% de sobrevivência
    **Homens na 3ª classe:** 13.54% de sobrevivência

## 🛠️ Tecnologias Utilizadas

-   Python 3.8+
-   Pandas - Manipulação de dados
-   Seaborn - Visualização de dados
-   Matplotlib - Criação de gráficos
-   Jupyter Notebook - Ambiente de análise

## 📋 Conclusões

A análise revelou que a sobrevivência no Titanic foi fortemente influenciada por:

**Classe social:** Passageiros de classes superiores tiveram prioridade nos botes salva-vidas

**Gênero:** A política "mulheres e crianças primeiro" foi amplamente seguida

**Idade:** Crianças tiveram maiores taxas de sobrevivência

## 👨‍💻 Autor

Vinícius Azevedo Monteiro

[LinkedIn](https://www.linkedin.com/in/vinicius-amonteiro/)

[GitHub](https://github.com/vinikev)

## 📊 Visualizações

**Distribuição de Sobrevivência**
![Distribuição de Sobrevivência](images/survival_distribution.png)

**Sobrevivência por Gênero**
![Sobrevivência por Gênero](images/survival_by_gender.png)

**Sobrevivência por Classe**
![Sobrevivência por Classe](images/survival_by_class.png)

**Mapa de Calor de Correlações**
![Mapa de Calor de Correlações](images/correlation_heatmap.png)

**Sobrevivência por Classe e Gênero**
![Sobrevivência por Classe e Gênero](images/survival_by_class_gender.png)
