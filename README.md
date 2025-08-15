# Dashboard de Dengue - Power BI

Este projeto apresenta um dashboard interativo desenvolvido no Power BI para a análise epidemiológica da dengue em Ribeirão Preto/SP, abrangendo o período de 2020 a 2025.  
O estudo correlaciona dados de incidência da doença com variáveis climáticas locais, buscando identificar possíveis relações e padrões.

## Funcionalidades
- Evolução dos casos de dengue ao longo do tempo
- Comparação entre anos e entre os mesmos trimestres
- Análise por trimestre (T1, T2, T3, T4) com filtros interativos
- Visualização de sazonalidade: destaque dos trimestres com maior incidência ligada à umidade
- Correlação estatística (coeficiente de Pearson) entre casos e variáveis climáticas (umidade e temperatura)
- Filtros temporais e por tipo de variável climática

## Acesse o Dashboard Online
Você pode visualizar o dashboard publicado no Power BI através do link:  
[**Abrir no Power BI**](https://app.powerbi.com/groups/me/reports/f20b4410-79ac-4c51-919e-99151cdee757?ctid=cf72e2bd-7a2b-4783-bdeb-39d57b07f76f&pbi_source=linkShare&bookmarkGuid=f22c0fda-031f-4c23-b69f-552e01616cae)

## Artigo no Medium
Para entender mais sobre a metodologia, padrões sazonais e correlações, leia o artigo completo:  
[**Análise epidemiológica da dengue em função de variáveis climáticas em Ribeirão Preto**](https://medium.com/@nicolasaws12/an%C3%A1lise-epidemiol%C3%B3gica-da-dengue-em-fun%C3%A7%C3%A3o-de-variáveis-climáticas-em-ribeir%C3%A3o-preto-536efb1724dd)

## Estrutura do Repositório
- `Arbovirose-DengueVS8 (1).pbix` → arquivo do Power BI
- `dados/` → arquivos CSV/XLSX utilizados no projeto
- `imagens/` → capturas de tela do dashboard
- `Dashboard_Dengue.pdf` → versão estática para visualização rápida

## Como Visualizar Localmente
1. Baixe o arquivo `.pbix`
2. Abra no Power BI Desktop (gratuito)
3. Explore os filtros e visualizações

## Capturas de Tela
![Visão Geral](imagem/Powerbi1arboviroeses.png)  
![Visão 2](imagem/Powerbi2arboviroses.png)

## Fontes dos Dados
- Casos de dengue: [VIGENT - Secretaria de Estado da Saúde de São Paulo](https://vigent.saude.sp.gov.br/sisawebinfo/)  
- Dados meteorológicos: [CIIAGRO](http://www.ciiagro.org.br/ema/)

## Observações
Os dados foram tratados e integrados exclusivamente para fins acadêmicos e de estudo.  
O dashboard é uma ferramenta de apoio para análise e visualização, não substituindo relatórios oficiais de saúde.
