# Análise do Mercado de Cafeterias com Garçons Robôs em Los Angeles

## Sobre o Projeto

Neste projeto, pretendemos analisar a viabilidade de abrir uma cafeteria inovadora com garçons robôs em Los Angeles. Através de uma pesquisa de mercado detalhada, buscamos compreender as condições atuais do setor de cafeterias, avaliar a concorrência e determinar se a novidade dos garçons robôs pode sustentar o negócio a longo prazo.

## Objetivo

Fornecer insights valiosos sobre o mercado de cafeterias em Los Angeles, identificando tendências, desafios e oportunidades. A finalidade é garantir que a ideia de garçons robôs seja sustentável, mantendo a cafeteria competitiva e atrativa mesmo após o declínio inicial da novidade.

## Etapas do Projeto

### 1. Introdução ao Projeto
- Visão geral da proposta e o conjunto de dados disponíveis.

### 2. Carregar e Preparar os Dados
- Importação do conjunto de dados `rest_data_us.csv`.
- Verificação e tratamento de dados ausentes, duplicados ou inconsistentes.

### 3. Análise de Dados
- Análise da proporção de tipos de estabelecimentos e comparação entre redes e independentes.
- Identificação das características predominantes das redes.
- Avaliação do número médio de assentos por tipo de restaurante.
- Análise dos endereços para determinar as ruas mais populares para restaurantes e aquelas com potencial inexplorado.

### 4. Utilização de Machine Learning
- Uso da biblioteca `recordlinkage` para identificar e tratar duplicatas implícitas através de análise de similaridade.

### 5. Preparar uma Apresentação
- Síntese das descobertas e recomendações em uma apresentação para potenciais investidores.

## Importação dos Dados

Nesta fase, carregamos as bibliotecas necessárias e procedemos com uma análise preliminar dos dados. As bibliotecas a serem utilizadas incluem:

- `pandas` para análise de dados.
- `numpy` para operações numéricas.
- `matplotlib.pyplot` para visualizações gráficas.
- `recordlinkage` para tratamento de duplicatas através de análise de similaridade.

```python
# Código de exemplo para importação das bibliotecas
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import recordlinkage
```

Após a importação das bibliotecas, procederemos com a abertura do conjunto de dados, seguido por etapas de pré-análise e processamento.

## Apresentação
https://drive.google.com/file/d/1A_UkNovv_WrH0Yycaiv3b1l8o6pbfbhe/view?usp=share_link
