# Projeto_T3_KNN

# Equipe 16

# Nome:
Onécio Araujo Ribeiro


# Análise de Dados do Instagram e Modelagem Preditiva usando k-Nearest Neighbors (kNN)
Visão Geral do Projeto
Este projeto tem como objetivo desenvolver um modelo preditivo usando o algoritmo k-Nearest Neighbors (kNN) para analisar dados do Instagram. O processo abrange a exploração de dados, desenvolvimento do modelo, otimização e validação. O conjunto de dados inclui vários atributos como rank, channel_info, influence_score, posts, followers, avg_likes, 60_day_eng_rate, new_post_avg_like, total_likes e country.

# Objetivos
Realizar uma análise exploratória dos dados (EDA) para identificar insights importantes e relações entre variáveis.
Transformar dados categóricos para modelagem eficaz.
Implementar e ajustar o algoritmo kNN para análise preditiva.
Otimizar o modelo usando técnicas como validação cruzada e ajuste de hiperparâmetros.
Validar o modelo usando métricas de desempenho padrão.

# Preparação dos Dados
Transformação de Países: Converter o atributo country em faixas numéricas baseadas em continentes para facilitar a interpretação de dados categóricos.
Valores Faltantes: Remover valores NaN para garantir a qualidade e confiabilidade do conjunto de dados.
Normalização: Padronizar características numéricas para melhorar o desempenho do algoritmo kNN.

# Análise Exploratória dos Dados
Examinou-se a relação entre followers e avg_likes.
Analisou-se o impacto de 60_day_eng_rate nas taxas de engajamento.
Visualizou-se os dados usando gráficos de dispersão e mapas de calor de correlação para identificar tendências e padrões importantes.

# Implementação do Modelo
Algoritmo: Utilizou-se o algoritmo k-Nearest Neighbors implementado com Scikit-Learn.
Teste de Parâmetros: Explorou-se uma gama de valores para k e métricas de distância (Euclidiana e Manhattan).
Validação: Empregou-se a validação cruzada para garantir a consistência e confiabilidade do modelo.

# Otimização e Avaliação
GridSearchCV: Usado para ajuste de hiperparâmetros e encontrar o valor ótimo de k.
Métricas de Desempenho: Avaliou-se o modelo usando erro absoluto médio (MAE), erro quadrático médio (MSE) e raiz do erro quadrático médio (RMSE).
Visualização dos Resultados: Criou-se gráficos informativos para exibir o desempenho do modelo, como gráficos de dispersão e gráficos de barras.

# Resultados
O modelo kNN otimizado previu com sucesso o influence_score, demonstrando uma capacidade robusta de generalizar insights a partir do conjunto de dados do Instagram. O projeto fornece uma estrutura para melhorias futuras, incluindo modelos que incorporam classificações de dados da Ásia, Oceania e África.

# Como Usar
Clone o repositório: git clone https://github.com/onecio/Projeto_T3_KNN
Importe o Data Frame do Projeto: "insta.csv"
Abra e execute o notebook em um ambiente Google Colab.
