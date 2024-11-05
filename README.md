
# Tech Challenge - Fase 1 - Regressão linear
Para esse tech challenge usei a base de dados de pessoas de diferentes gêneros e idades, se são fumantes ou não, tem filhos e qual seu IMC (índice de massa corporal) conforme ideia fornecida para a atividade. <br>
Com base nesses dados, cria-se um modelo preditivo de regressão para prever custos médicos individuais dessas pessoas.

Etapas do desenvolvimento do Tech Challenge:

1. Exploração dos dados:

* carregamento da base de dados;
* exploração das características da base de dados (ex: colunas, tipos de dados).
* análise das estatísticas descritivas (como média e desvio padrão) e visualizar distribuições relevantes (histogramas, boxplots e pairplot).

2. Pré-processamento dos Dados:

* limpeza de dados: tratamento de valores ausentes caso houver (nesse caso estipulei valores exatos na criação da tabela, mas no mundo real deve-se ser tratado valores nulos, como por exemplo, substituir valores nulos com 0 usando df.fillna(0) ou uso de medianas de valores).

* conversão de variáveis categóricas: transformei variáveis como "gênero" e "região" em numéricas (usando one-hot encoding).

* escolha de técnica de regressão: Regressão Linear

* divisão dos dados em conjuntos de treinamento e teste (ex: 80% dos dados foram usados para treino e 20% para teste).

3. Treinamento e Avaliação:

* Treinar o modelo com o conjunto de treinamento.
* Avaliar o desempenho do modelo com o conjunto de teste usando métricas como R², MSE, MAE.
  
4. Validação Estatística:

* Análise dos resultados e verificação de se o modelo atende aos requisitos de precisão e confiabilidade.
5. Insights conclusivos
