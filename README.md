
**Problemática**

A MR HEALTH é uma rede de “Slow-Food” presente na região sul e com aproximadamente 50 unidades e gostariade  adotar modelos estatísticos para gestão dos estoques de suas unidades


**Dicionário de Dados**

ITEM_PEDIDO-_2_.xlsx
- ID_PEDIDO [string]: identificação do pedido
- ID_ITEM [string]: identificação do item
- QUANTIDADE [int]: quantidade de itens vendidos

PEDIDO-_1_.xlsx
- ID_PEDIDO [string]: identificação do pedido
- DATA [date]: data do pedido
- VALOR_TOTAL [float]: valor total do pedido

ITENS-_3_.xlsx
- ID_ITEM [string]: identificação do item
- 0 [float]: Valor dos itens


**Arquitetura**
- 01-eda.ipynb: script com os artefatos da análise e exploração de dados
- 02-model.ipynb: script com o desenvolvimento do modelo Média Móvel Simples, Regressão Linear e Random Forest


**Insights**

- O intervalo de análise é de junho à agosto de 2021
- Vendemos em 220 items totalizando em média R$ 5236
- O ticket média mensal da empresa tem uma leve tendência de crescimento seguido de uma possível estabilização
- Em 3 meses saímos de 74 reais para 94 reais, representando um aumento de 27%
- O item D é responsável por aproximadamente 40% das vendas da empresa seguindo do item C com 26%
- O item D é o mais vendido, seguido do item B
- O ciclo médio de compra é de aproximadamente 1.26 dias
- Foi possível desenvolver um modelo com erro em média de 2 items



**Próximos passos**
- Modelos mais robustos
- Apresentação do resultado em comparação do dia anterior
- Apresentar o resultado em termos financeiro