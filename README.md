# BankPulse: Analyzing Liquidity, Risk, and NPAs in Indian Banking

## Overview

**BankPulse** is a data-driven financial analytics project aimed at evaluating the **liquidity creation**, **non-performing assets (NPAs)**, and **insolvency risk** in the Indian banking sector. The project leverages panel regression models to uncover the key determinants affecting the financial health and stability of **public**, **private**, and **foreign** banks operating in India.

---

## Objectives

- Analyze the trends in liquidity creation and insolvency risk across different types of banks.
- Examine the evolution of NPAs and assess their impact on financial stability.
- Identify the key financial and macroeconomic variables influencing liquidity and risk.
- Use econometric models to derive statistically significant insights on determinants like:
  - **Loan growth**
  - **Deposit growth**
  - **Bank size**
  - **Net interest margin**
  - **Capital adequacy ratio**

---

##  Methodology

### Data Preparation
- Constructed a panel dataset of Indian banks using multiple financial indicators.
- Created the following derived variables:
  - **Z-Score**: Proxy for insolvency risk
  - **Liquidity Creation Metrics**: Based on four established definitions in literature

### Econometric Models
- Implemented the following regression models using Python (`statsmodels`, `linearmodels`):
  - Fixed Effects Model
  - Random Effects Model
  - Pooled OLS

---

## Key Insights

- **Liquidity Creation Trends**: Vary significantly between public, private, and foreign banks.
- **Z-Score Analysis**: Public sector banks tend to have lower Z-scores (higher risk).
- **Determinants of Risk and NPAs**: Loan growth and capital adequacy are found to be significant predictors.

---

## Tech Stack

- **Language**: Python
- **Libraries**:
  - `pandas`, `numpy` – Data processing
  - `statsmodels`, `linearmodels` – Econometric modeling
  - `matplotlib`, `seaborn` – Data visualization


