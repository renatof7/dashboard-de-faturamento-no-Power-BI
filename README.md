# Dashboard de Faturamento no Power BI

Projeto de análise de faturamento desenvolvido no Power BI com foco em acompanhar indicadores comerciais e financeiros de vendas. O dashboard consolida informações por produto, país, segmento e período, permitindo uma visão clara sobre receita, lucro, descontos e volume vendido.

## Sobre o projeto

Este projeto foi construído a partir de uma base transacional de vendas contendo informações sobre segmentos de clientes, países, produtos, faixas de desconto e calendário. O objetivo foi transformar esses dados em um relatório gerencial para apoiar análises de desempenho comercial.

O dashboard apresenta indicadores estratégicos e visuais interativos para facilitar a leitura dos resultados e identificar padrões de vendas, lucratividade e distribuição dos produtos.

## Objetivo

O projeto tem como objetivo monitorar o desempenho de vendas e apoiar a tomada de decisão por meio de indicadores de faturamento, lucro e volume comercializado.

Entre os principais usos do dashboard estão:

- análise de evolução das vendas ao longo do tempo;
- comparação de desempenho entre produtos;
- avaliação do impacto de descontos;
- análise por país e segmento de cliente;
- acompanhamento de indicadores financeiros e comerciais.

## Dados utilizados

A base contém informações como:

- `Segment`: segmento de cliente
- `Country`: país
- `Product`: produto
- `Discount Band`: faixa de desconto
- `Units Sold`: unidades vendidas
- `Manufacturing Price`: custo de fabricação
- `Sale Price`: preço de venda
- `Gross Sales`: vendas brutas
- `Discounts`: descontos
- `Sales`: vendas líquidas
- `COGS`: custo dos produtos vendidos
- `Profit`: lucro
- `Date`: data da venda
- `Month Number`, `Month Name`, `Year`: informações de calendário

## Principais indicadores do dashboard

Com base no relatório apresentado:

- **Vendas totais:** 118,73 Mi
- **Lucro total:** 16,89 Mi
- **Unidades vendidas:** 1,13 Mi

O dashboard também permite visualizar:

- evolução das vendas por ano, trimestre e mês;
- distribuição de unidades vendidas por produto;
- comparação entre vendas e descontos por país;
- comparação entre vendas e descontos por produto;
- filtro por segmento de cliente.

## Visuais desenvolvidos

O relatório inclui os seguintes componentes:

- cards com KPIs principais;
- gráfico de linha para evolução temporal das vendas;
- gráfico de pizza para participação de unidades vendidas por produto;
- mapa para análise geográfica de vendas e descontos;
- gráfico de colunas para comparação entre vendas e descontos por produto;
- segmentação por tipo de cliente.

## Tecnologias e ferramentas

- Power BI
- Excel
- Modelagem de dados
- Visualização de dados
- Business Intelligence

## Estrutura do projeto

```bash
dashboard-faturamento-powerbi/
├─ base_faturamento.xlsx
├─ faturamento.pbix
├─ assets/
│  └─ faturamento.jpg
└─ README.md
```

## Possíveis análises de negócio

Este dashboard pode ser utilizado para:

- identificar os produtos com maior participação nas vendas;
- analisar tendências de faturamento ao longo do tempo;
- comparar desempenho entre países;
- avaliar o efeito dos descontos sobre o resultado financeiro;
- entender quais segmentos geram mais valor para o negócio.

## Próximos passos

- incluir indicadores por margem de lucro;
- criar comparativos entre períodos;
- adicionar metas e variação percentual;
- aprofundar análises por segmento e país;
- melhorar a navegação do relatório com páginas adicionais.

## Dashboard

![Dashboard de faturamento](./assets/faturamento.jpg)

## Autor

Projeto desenvolvido para fins de estudo e portfólio na área de dados, BI e análise de negócios.
