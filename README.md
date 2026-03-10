# 📡 TelecomX: Previsão de Churn com Machine Learning

![Status do Projeto](https://img.shields.io/badge/Status-Concluído-brightgreen)
![Linguagem](https://img.shields.io/badge/Python-3.8+-blue)

Este projeto foi desenvolvido para identificar clientes com alto risco de evasão (Churn) na empresa **TelecomX**. Através de técnicas de Ciência de Dados e Machine Learning, buscando prever cancelamentos e fornecer insights acionáveis para o time de retenção fictício.

## Visão Geral
O Churn é um dos principais desafios no setor de telecomunicações. Neste projeto, foi tirado dados de comportamento dos clientes, aplicado preparação e tratamento de dados e treinado modelos de machine learning para classificar potenciais desistências com base em padrões históricos.

## Resultados do Modelo
Após o ajuste de hiperparâmetros buscando evitar *overfitting*, foi alcançado as seguintes métricas:

| Métrica | Resultado |
| :--- | :--- |
| **Acurácia** | 77.12% |
| **Recall (Churn)** | 49.00% |
| **Precisão (Churn)** | 60.00% |

> **Nota:** O modelo é capaz de capturar aproximadamente 50% de todos os cancelamentos reais, permitindo uma economia significativa através de campanhas de retenção direcionadas.

## Variáveis Mais Influentes
Abaixo, o gráfico de importância das variáveis gerado pelo modelo:

<img width="1191" height="705" alt="baixados" src="https://github.com/user-attachments/assets/9f06b8c1-8c70-49d9-a0fc-6e6eee7bb313" />


### Principais Insights:
1. **Tipo de Contrato:** Clientes com contratos mensais (*Month-to-month*) têm 4x mais chances de churn do que contratos de longa duração.
2. **Serviço de Internet:** A tecnologia de Fibra Óptica apresenta uma taxa de evasão acima da média, sugerindo problemas de preço ou estabilidade.
3. **Serviços Adicionais:** Clientes sem suporte técnico ou segurança online tendem a ser menos fiéis.

## Tecnologias e Ferramentas
- **Python** (Pandas, Numpy)
- **Scikit-Learn** (Random Forest, Metrics, StandardScaler...)
- **Matplotlib & Seaborn** (Visualização de Dados)
- **Google Colab** (Ambiente de Desenvolvimento)

## Como Executar o Projeto
O notebook está configurado para ler os dados diretamente deste repositório via URL Raw. 
1. Clique no botão "Open in Colab" no topo do arquivo `.ipynb`.
2. Execute as células sequencialmente.

---
Desenvolvido por Vitor Silva
