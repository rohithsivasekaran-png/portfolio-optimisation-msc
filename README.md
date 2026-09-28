# Multi-Asset Portfolio Optimisation — MSc Finance (DCU)

# Overview
A quantitative portfolio construction and analysis project built in Python as part of the MSc Finance programme at Dublin City University (2026).

# Project Summary
This project constructs and analyses a **12-asset multi-regime portfolio** across three distinct market periods (2015–2024), using constrained optimisation, Monte Carlo simulation, VaR analysis, and ESG integration.

# Assets
| Category | Assets |
|---|---|
| Equities | SPY (S&P 500), Nifty 50, Sony, BMW, Tencent, BYD |
| Fixed Income | US Treasury ETF (IEF) |
| Commodities | Gold, Silver, Crude Oil |
| FX | EUR/USD |
| Digital Assets | Bitcoin |

# Market Regimes
- **Regime 1 (2015–2018):** Stable bull market
- **Regime 2 (2019–2020):** COVID-19 market shock
- **Regime 3 (2021–2024):** Recovery with inflationary pressures

# Key Methods
- Minimum Variance Portfolio (MVP) optimisation
- Maximum Sharpe Ratio Portfolio (MSP) optimisation
- Monte Carlo simulation (10,000 portfolios)
- Value-at-Risk (VaR) at 99%, 95%, and 90% confidence levels
- OLS regression — alpha & beta vs S&P 500
- ESG-constrained portfolio optimisation

# Key Results
- MVP generated **alpha of 0.49%/month** vs S&P 500
- MSP generated **alpha of 1.12%/month** vs S&P 500
- ESG portfolio achieved **19.2% return vs 19.4%** for original MSP — near-identical performance with lower risk
- Both portfolios showed **beta below 0.5** — significantly less sensitive to market movements than the benchmark

# Tools & Libraries
Python · pandas · numpy · scipy · statsmodels · matplotlib · seaborn · yfinance

# Author
**Rohith Sivasekaran**
MSc Finance — Dublin City University
[LinkedIn](https://www.linkedin.com/in/rohithsivasekaran/)
