# Challenge Alura Store

# Análise de Desempenho das Lojas

No **Challenge Alura Store**, foi realizada uma análise detalhada das lojas, levando em consideração os critérios (métricas) como **faturamento**, **avaliação dos clientes**, **frete médio**, **ticket médio** e **pontuação total**. A análise visou determinar qual loja (dentre as 4 lojas disponíveis) apresenta o melhor desempenho com base em diferentes métricas.

## 1. **Preparação e Carregamento dos Dados**

Foi realizada a leitura dos dados das lojas, onde cada uma delas estava em um arquivo separado (`loja1.csv`, `loja2.csv`, `loja3.csv`, `loja4.csv`). Esses dados foram carregados em um **DataFrames do pandas**, e as colunas consideradas para a análise foram:

- Produto;
- Categoria do Produto;
- Preço;
- Frete;
- Data da Compra;
- Vendedor;
- Local da compra;
- Avaliação da compra;
- Tipo de pagamento;
- Quantidade de parcelas;
- Latitude (lat) e
- Longitude (lon)

## 2. **Análise do Faturamento das Lojas**

Inicialmente, foi feito um cálculo do **faturamento total** considerando todas as 4 lojas. O faturamento foi obtido somando o **preço** de cada produto mais o **valor do frete** e somando tudo ao total.

Além disso, foi criada uma análise do **faturamento anual**, agrupando os dados por ano para observar as tendências de vendas ao longo do tempo.

## 3. **Faturamento por Categoria e Produto**

Foi realizada uma análise do **faturamento por categoria** e **faturamento por produto**. O objetivo foi entender quais categorias e quais produtos estavam gerando mais receita. Com isso, foi possível gerar gráficos de **barras** para visualizar os resultados de maneira mais clara e objetiva.

## 4. **Análise do Frete**

Foi calculado o **frete médio** por loja, com a finalidade de analisar como os custos de envio variam entre as lojas e se algum ajuste é necessário para tornar os fretes mais competitivos. O **frete médio** foi plotado em gráficos de barras para uma análise visual.

## 5. **Média de Avaliação das Lojas**

A média de avaliação dos clientes para cada loja foi calculada, levando em consideração as avaliações fornecidas nas compras. Foi gerado um gráfico de barras para visualizar as diferenças na média de avaliação entre as lojas.

## 6. **Análise da Melhor Loja**

Com base na pontuação total, calculada a partir de vários critérios (faturamento, número de vendas, frete médio, etc.), foi identificado que a **Loja 2** obteve o melhor desempenho, com uma pontuação de **3.54**. A **Loja 3** ficou logo abaixo, com uma pontuação de **3.53**, seguida pela **Loja 1** (pontuação de **3.00**) e, por último, a **Loja 4**, com uma pontuação de **1.27**.

A **Loja 4** foi a que apresentou os piores resultados em todas as métricas avaliadas, ficando **64.15% abaixo** da **Loja 2** em termos de pontuação total.

## 7. **Cálculo da Diferença Percentual (Loja 4 em relação à Loja 2)**

A **Loja 4** foi analisada em relação à **Loja 2** para entender o quão abaixo ela está em termos de pontuação total. O cálculo mostrou que a **Loja 4** está **64.15% abaixo** da **Loja 2**.

## 8. **Melhoria dos Resultados da Loja 4**

Foram propostas diversas estratégias para **melhorar os resultados da Loja 4**, incluindo:

- Aumento a visibilidade da loja por meio de campanhas de marketing (digital e não digital);
- Oferecer promoções sazonais;
- Oferecer descontos em compras múltiplas e frete grátis para compras acima de R$ 300,00 (por exemplo);
- Melhorar o atendimento ao cliente (focando nas correções das reclamações de transporte, armazenamento, e tempo de atendimento).
