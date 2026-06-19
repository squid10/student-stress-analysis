# Análise de Dados: Monitoramento de Estresse em Estudantes
### Projeto de Data Science & Business Intelligence

![Status](https://img.shields.io/badge/Status-Finalizado-success)
![Power BI](https://img.shields.io/badge/Power_BI-Dark_Mode-yellow)
![Python](https://img.shields.io/badge/Python-Pandas_|_Seaborn-blue)

##  Sobre o Projeto
Este projeto tem como objetivo analisar os níveis de estresse em estudantes universitários, identificando correlações entre hábitos de sono, carga de estudos e fatores psicológicos. O trabalho foi desenvolvido alinhado aos **Objetivos de Desenvolvimento Sustentável (ODS)** da ONU, focado em Saúde e Bem-Estar (ODS 3).

O diferencial técnico deste projeto é a integração híbrida entre **Power BI** e **Python**, utilizando scripts visuais para gerar gráficos estatísticos avançados (Matriz de Correlação, Violin Plots) que não existem nativamente na ferramenta da Microsoft.

## Arquitetura e Tecnologias
1.  **Coleta de Dados:** Dataset público (Kaggle) sobre *Student Stress Factors*.
2.  **Engenharia de Dados (ETL):**
    * Ambiente: **Google Colab**.
    * Linguagem: **Python (Pandas)** para limpeza, tratamento de nulos e normalização.
    * Armazenamento: **Google Cloud Storage (GCS)** via API para datalake.
3.  **Visualização e Storytelling:**
    * **Power BI:** Dashboard interativo com 3 páginas (Panorama, Diagnóstico, IA).
    * **Python Visuals:** Matriz de Correlação (Seaborn) e Violin Plots integrados ao report.
    * **Design:** Layout personalizado "Dark Mode Tech" gerado via Matplotlib.

## Estrutura do Dashboard

### Página 1: Panorama Geral
Visão macro dos dados demográficos e os principais ofensores (Top 10 Fatores de Estresse).
* *KPIs:* Total de Alunos, Média de Idade.
* *Destaque:* Classificação entre Eustress (Positivo) vs Distress (Negativo).

### Página 2: Diagnóstico e Fatores de Risco
Análise profunda de correlações estatísticas.
* **Matriz de Correlação (Python):** Mapa de calor mostrando conexões entre variáveis (ex: Sono x Ansiedade).
* **Scatter Plot:** Relação direta entre Qualidade do Sono e Nível de Ansiedade.

### Página 3: Inteligência Artificial e Padrões
Uso de algoritmos para predição e análise de distribuição.
* **Principais Influenciadores (IA):** O que faz o estresse aumentar ou diminuir?
* **Violin Plot (Python):** Distribuição de densidade da ansiedade por tipo de estresse.

## Como Executar
1.  Clone este repositório.
2.  Os dados tratados estão na pasta `datasets/`.
3.  Abra o arquivo `Dashboard_Estresse.pbix` no Power BI Desktop.
    * *Nota:* Para que os visuais Python funcionem, é necessário ter Python instalado com as bibliotecas: `pandas`, `matplotlib`, `seaborn`.

## Resultados Chave
* Identificou-se que a **Qualidade do Sono** é o fator de proteção #1 contra a ansiedade.
* Alunos com histórico de saúde mental apresentam níveis de *Distress* significativamente maiores, exigindo atenção institucional.

---
*Desenvolvido por Ângelo - 2025*
