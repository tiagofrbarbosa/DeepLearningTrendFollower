# 💡 Deep Learning e Ciência de Dados aplicados ao Mercado Financeiro

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Projeto desenvolvido como requisito do **MBA em Ciência de Dados e IA – FIAP**.  
O case simula o ambiente da **Quantum Finance**, uma fintech fictícia, e tem como objetivo construir um **modelo _Trend Follower_** capaz de gerar sinais de **compra** e **venda** a partir das oscilações recentes de ativos do mercado de capitais.

---

## ⚙️ Abordagem Técnica

| Etapa | Descrição | Principais Ferramentas/Modelos |
|-------|-----------|--------------------------------|
| **1. Feature Engineering** | Extração automática de estatísticas e padrões relevantes das séries temporais. | **TSFresh** |
| **2. Modelagem Deep Learning** | Captura de dependências temporais e espaciais nos dados. | **CNN 1D**, **LSTM** |
| **3. Representação em Imagens** | Conversão das séries para **Gramian Angular Fields (GAF)** e exploração de correlações visuais. | **CNN 2D** |
| **4. Validação & Backtesting** | Simulação de operações reais para medir _drawdown_, _sharpe ratio_ e retorno acumulado. | **Backtests financeiros** |
| **5. Estratégia** | Implementação de lógica **Trend Follower** baseada nos sinais preditos. | Python |

---

## 🚀 Resultados

- **Precisão elevada** na identificação de tendências de curto prazo.  
- **Redução do _lag_ de decisão** comparada a indicadores clássicos.  
- **Estratégia replicável** para outros ativos e janelas temporais.

---

📜 Licença
Distribuído sob a licença MIT — sinta-se à vontade para usar, modificar e distribuir para fins acadêmicos ou pessoais. Veja o arquivo LICENSE para mais detalhes.
