# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Nesse desafio de projeto "Previsão de Estoque Inteligente na AWS com SageMaker Canvas, vamos aprender a usar o SageMaker Canvas para criar previsões de estoque baseadas em Machine Learning (ML) através dos passos abaixo!

## 📋 Pré-requisitos

Ter uma conta na AWS. Repositório para lhe ajudar a criar uma conta: [AWS Cloud Quickstart](https://github.com/digitalinnovationone/aws-cloud-quickstart).
Atendido, conta criada na AWS com sucesso!
Em seguida, acessar o AWS Console Management e o SageMaker Canvas. Depois, criar um domínio para começar o Projeto.


## 🎯 Objetivos deste Desafio de Projeto (Lab)

![image](https://github.com/digitalinnovationone/lab-aws-sagemaker-canvas-estoque/assets/730492/72f5c21f-5562-491e-aa42-2885a3184650)

- Após o fork deste projeto, reescreva o `README.md` do seu jeito.
- Siga o passo a passo a seguir para desenvolver seu projeto em ML no-code com o Amazon SageMaker Canvas.
- Ao final, envie a URL do seu repositório com a solução na plataforma da DIO.


## 🚀 Passo a Passo

### 1. Selecionar Dataset

-   Navegue até a pasta `datasets` deste repositório. Esta pasta contém os datasets para escolher, treinar e testar seu modelo de ML.
-   Foi escolhido o `dataset` _dataset-1000-com-preco-variavel-e-renovacao-estoque.csv_.
-   Faça o upload do dataset no SageMaker Canvas. Feito!

### 2. Construir/Treinar

-   No SageMaker Canvas, importe o dataset que você selecionou. Feito!
-   Configure as variáveis de entrada e saída de acordo com os dados. Feito!
-   Inicie o treinamento do modelo. Isso pode levar algum tempo, dependendo do tamanho do dataset. Escolhido o quick build para o novo modelo time-series forecast para 02 dias, limite de 09 dias!

### 3. Analisar

-   Após o treinamento, as métricas de performance do modelo foram: Avg. wQL = 0.070, MAPE = 0.119, RMSE = 1.728, MASE = 0.888
-   Verifique as principais características que influenciam as previsões. Influência de 44.63% de QUANTIDADE_ESTOQUE.
-   Como o desempenho foi satisfatório, não foi feito o retreino.

### 4. Prever

-   Use o modelo treinado para fazer previsões de estoque. Feitas previsões simples para alguns itens.
-   Exporte os resultados e analise as previsões geradas. Feito!
-   Documente suas conclusões e qualquer insight obtido a partir das previsões. Como a previsão foi feita para 02 dias a frente, percebe-se que os gráficos fazem curva.

## Conclusões

A experiência de aprendizado de Machine Learning com o AWS SageMaker Canvas / Studio foi enriquecedora e foi atingido o objetivo de se aliar teoria e prática.
