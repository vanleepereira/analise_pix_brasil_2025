📊 Análise de Transações PIX (Brasil - 2025)
Este projeto apresenta uma análise completa (ponta a ponta) do sistema de pagamentos PIX no Brasil durante o ano de 2025. O objetivo principal é identificar padrões de comportamento entre Pessoas Físicas (PF) e Pessoas Jurídicas (PJ), além de observar a distribuição regional e o crescimento mensal das transações.

Link do dashboard: https://app.powerbi.com/view?r=eyJrIjoiYTRmMjliOTYtOGE3My00ZDJkLWE4ODYtNTU4Nzg4ZGUzMzRjIiwidCI6IjY2OWExOTdhLTA5NTQtNDdmZC1hN2IwLTkxMDEyNDZlN2YwZCJ9 


🚀 Estrutura do Projeto
O projeto foi dividido em três etapas principais:

Extração e ETL (Python): Tratamento dos dados brutos em formato JSON extraídos do portal de Dados Abertos do Banco Central.

Modelagem de Dados: Estruturação em Star Schema para otimização de performance e filtros dinâmicos.

Visualização (Power BI): Criação de um dashboard interativo para análise de KPIs, volumetria e tendências sazonais.

🛠 Tecnologias Utilizadas
Python (Pandas): Limpeza, tipagem, tratamento de valores nulos e exportação dos dados.

Power BI: Desenvolvimento de relatórios, medidas em DAX e modelagem relacional.

JSON/CSV: Manipulação de estruturas de dados semi-estruturadas e conversão para tabelas fato.

📂 Arquivos do Repositório
bc_pix.ipynb: Jupyter Notebook com toda a lógica de transformação dos dados (ETL).

pix_municipios_2025_final.csv: Dataset processado e estruturado utilizado no dashboard.

quantidade pix.pbix: Arquivo do Power BI com o relatório final completo.


📈 Principais Insights
Maturidade Comercial: O volume financeiro recebido por Pessoas Jurídicas (PJ) demonstra a consolidação do PIX como ferramenta essencial de negócios no Brasil.

Distribuição Regional: Análise detalhada por Região, Estado e Município, identificando os principais polos de movimentação financeira.

Sazonalidade: Observação do crescimento constante na adesão ao método de pagamento ao longo dos meses.

👤 Autor
Van Lee Pereira Tradutor, Professor de Inglês e Analista de Dados em formação.

Nota: Os dados utilizados neste projeto são de origem pública, disponibilizados pelo Banco Central do Brasil. O arquivo JSON original (devido ao tamanho) foi processado para gerar o arquivo CSV final presente neste repositório.
