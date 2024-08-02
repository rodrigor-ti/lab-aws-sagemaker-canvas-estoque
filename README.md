# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Bem-vindo ao desafio de projeto "Previsão de Estoque Inteligente na AWS com SageMaker Canvas. Neste Lab DIO, você aprenderá a usar o SageMaker Canvas para criar previsões de estoque baseadas em Machine Learning (ML). Siga os passos abaixo para completar o desafio!

## 📋 Pré-requisitos

Antes de começar, certifique-se de ter uma conta na AWS. Se precisar de ajuda para criar sua conta, confira nosso repositório [AWS Cloud Quickstart](https://github.com/digitalinnovationone/aws-cloud-quickstart).


## 🎯 Objetivos Deste Desafio de Projeto (Lab)

![image](https://github.com/digitalinnovationone/lab-aws-sagemaker-canvas-estoque/assets/730492/72f5c21f-5562-491e-aa42-2885a3184650)

- Dê um fork neste projeto e reescreva este `README.md`. Sinta-se à vontade para detalhar todo o processo de criação do seu Modelo de ML para uma "Previsão de Estoque Inteligente".
- Para isso, siga o [passo a passo] descrito a seguir e evolua as suas habilidades em ML no-code com o Amazon SageMaker Canvas.
- Ao concluir, envie a URL do seu repositório com a solução na plataforma da DIO.


## 🚀 Passo a Passo

### 1. Selecionar Dataset

-   Navegue até a pasta `datasets` deste repositório. Esta pasta contém os datasets que você poderá escolher para treinar e testar seu modelo de ML. Sinta-se à vontade para gerar/enriquecer seus próprios datasets, quanto mais você se engajar, mais relevante esse projeto será em seu portfólio.
-   Escolha o dataset que você usará para treinar seu modelo de previsão de estoque.
-   Faça o upload do dataset no SageMaker Canvas.

### 2. Construir/Treinar

-   No SageMaker Canvas, importe o dataset que você selecionou.
-   Configure as variáveis de entrada e saída de acordo com os dados.
-   Inicie o treinamento do modelo. Isso pode levar algum tempo, dependendo do tamanho do dataset.

### 3. Analisar

-   Após o treinamento, examine as métricas de performance do modelo.
-   Verifique as principais características que influenciam as previsões.
-   Faça ajustes no modelo se necessário e re-treine até obter um desempenho satisfatório.

### 4. Prever

-   Use o modelo treinado para fazer previsões de estoque.
-   Exporte os resultados e analise as previsões geradas.
-   Documente suas conclusões e qualquer insight obtido a partir das previsões.

### 5. Resultado do DataSet 🎯🎯
Resultado da Análise
Dataset analisado: datasets/dataset-1000-com-preco-variavel-e-renovacao-estoque.csv

Métricas de desempenho do modelo:

Média wQL: 0,259

Isso indica que o modelo possui uma boa precisão.
MAPE (Erro Percentual Médio Absoluto): 1,803

O MAPE mede a diferença percentual média entre os valores previstos e os reais. Um valor menor indica um modelo mais preciso, sendo MAPE=0 o ideal. Com um MAPE de 1,803, podemos afirmar que o modelo não é perfeito e apresenta erros.
WAPE (Erro Percentual Absoluto Ponderado): 0,378

O WAPE avalia o desvio geral entre os valores previstos e os observados, normalizando pelo total da meta absoluta. Um valor menor é desejável, com WAPE=0 indicando perfeição. Com um WAPE de 0,378, o modelo é considerado excelente e praticamente sem erros.
RMSE (Erro Quadrático Médio): 29,146

Esse valor representa a raiz da média dos erros quadrados, sugerindo que o modelo possui erros significativos.
MASE (Erro Médio em Escala Absoluta): 1,393

Um MASE maior que 1 indica que o modelo é inferior à linha de base. Neste caso, o valor de 1,393 sugere que o desempenho do modelo é insatisfatório.

Esses resultados destacam a precisão relativa do modelo em algumas métricas, mas também indicam áreas onde ele pode ser melhorado para reduzir os erros.


Agradeço a oportunidade!!!








  
