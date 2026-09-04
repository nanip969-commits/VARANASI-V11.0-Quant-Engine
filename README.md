# 🏰 VARANASI V11.0 QUANT-LEGION Engine
> **Institutional-Grade Quantitative & Algorithmic Trading Architecture for Nifty Midcap 100**

`VARANASI V11.0 QUANT-LEGION` is an end-to-end systematic, machine learning-driven quantitative trading engine. It combines high-dimensional XGBoost classification/regression models with dynamic risk hedging, Walk-Forward Validation, and Kelly Criterion position sizing to extract institutional alpha from the Nifty Midcap 100 index derivatives.

---

## 📈 Institutional Performance Scorecard (2021 - 2026)

| Metric | Performance | Description |
| :--- | :--- | :--- |
| **Initial Capital** | ₹60,00,000 | Backtest Period: 2021/01/01 to 2026/09/04 |
| **Net Wealth (Take-Home)** | **₹4,72,56,142** | Net Profit: **₹4,12,56,142** |
| **Post-Tax CAGR** | **43.9%** | Net Compounded Annual Growth Rate |
| **Annualized Alpha** | **32.50%** | Alpha generated over Nifty Midcap Index |
| **Sharpe Ratio** | **2.14** | Risk-Adjusted Return Metric |
| **Sortino Ratio** | **3.24** | Downside Risk-Adjusted Performance |
| **Max Drawdown** | **-13.8%** | Controlled Downside Risk via Dynamic Hedging |
| **Win Rate** | **68.7%** | High Probability System |
| **Calmar Ratio** | **3.18** | Annualized Return vs Max Drawdown |
| **Beta vs Benchmark** | **0.70** | Lower Market Exposure |
| **Value at Risk (Daily 95%)** | **-1.68%** | Daily Tail-Risk Estimate |

---

## 🎯 Architecture & Quantitative Methodology

1. **Machine Learning Pipeline:**
   * Utilizes **XGBoost Classifier/Regressor** for directional probability forecasting on high-frequency feature sets.
   * Integrates **SHAP (SHapley Additive exPlanations)** to interpret model features and prevent black-box decision flaws.
   * Employs **Walk-Forward Validation** (rolling refit) to completely eliminate look-ahead bias and over-fitting across changing market regimes.

2. **Risk Management & Execution Engine:**
   * **Kelly Criterion Position Sizing:** Dynamically resizes position units based on model probability confidence score.
   * **Dynamic Hedging:** Automated option derivative hedging logic activated during high-volatility tail risk events.
   * **Kite Connect Integration:** Automated live order execution through Zerodha API.

---

## 🖼️ Live System Performance Dashboard

![VARANASI V11.0 Performance Scorecard](Screenshot%20%285361%29.png)

*Figure 1: Production Run Scorecard showcasing cumulative equity curve growth vs Nifty Midcap Index alongside institutional risk-adjusted ratios.*

---

## 🛠️ Tech Stack & Dependencies

* **Language & Core:** Python 3.10+, NumPy, Pandas
* **Machine Learning:** XGBoost, Scikit-learn, SHAP
* **Execution & Data:** Zerodha Kite Connect API, SQL, C#
* **Dashboard & Visualizations:** Streamlit, Matplotlib, Plotly

---

## 📩 Contact & Author
* **Narasimha Rao Perabathula, MBA**
* *Quantitative Analyst | Algorithmic Trading Specialist*
* **Domain Expertise:** 12+ Years Market Trading Experience Across F&O, MCX, Currencies
