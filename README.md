# Bitcoin and Macro Sensitivity Analysis (2017–2025)

## Project Overview
This project investigates whether Bitcoin behaves as a traditional risk-on financial asset by analyzing its relationship with key macro-financial variables:

- NASDAQ (equity market proxy)
- U.S. Dollar Index (DXY)
- Federal Funds Rate changes

## Methodology
1. Data collection using Yahoo Finance (yfinance) and FRED.
2. Data cleaning and alignment across daily frequency.
3. Feature engineering (log returns, Fed changes, rolling correlations).
4. OLS regression analysis to estimate macro sensitivity.

## Key Findings
- Bitcoin exhibits strong and statistically significant equity market sensitivity.
- Bitcoin moves inversely to U.S. dollar strength.
- Daily monetary policy shocks are not statistically significant.
- Macro variables explain approximately 8% of daily Bitcoin return variation.

## Tools Used
- Python (pandas, numpy, statsmodels, matplotlib)
- Jupyter Notebook
- Git & GitHub