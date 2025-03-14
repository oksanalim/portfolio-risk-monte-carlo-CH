# Portfolio Risk Analysis Monte Carlo Simulation (Swiss Market)

## Overview
This project utilizes Monte Carlo simulations to perform portfolio risk analysis tailored specifically for the Swiss market. It evaluates potential portfolio performance and risk by simulating asset returns, calculating expected losses, Value at Risk (VaR), and Expected Shortfall (Conditional VaR).

## Objectives
- Simulate future returns based on historical Swiss market data.
- Estimate key risk metrics such as Expected Loss, VaR, and Expected Shortfall.
- Visualize the simulated risk distribution clearly.

## Project Structure
```
portfolio-risk-monte-carlo-CH/
│── data/
│   │── swiss_stocks_data.csv
│── notebooks/
│   │── monte_carlo_analysis.ipynb
│── src/
│   │── monte_carlo_simulation.py
│── results/
│   │── simulation_results.csv
│── README.md

```
## Data Sources
- Historical financial data sourced from SIX Swiss Exchange and Yahoo Finance.
- Swiss market-specific securities (e.g., Nestlé, Roche, Novartis, UBS).

## Methodology
- Asset returns simulation based on historical data.
- Calculation of Expected Loss, Value at Risk (VaR), and Expected Shortfall.
- Visualization of potential loss distribution.

## Dependencies
Install required Python libraries:
```bash
pip install numpy pandas matplotlib seaborn yfinance
```

## Usage
Run the Monte Carlo simulation notebook in the `notebooks` directory:

```bash
jupyter notebook notebooks/monte_carlo_analysis.ipynb
```

## Swiss Market Adaptation
This project focuses on Swiss financial assets, using data in CHF and accounting for Swiss-specific market factors, such as currency fluctuations, interest rates, and regulatory considerations.

## Future Enhancements
- Integration of stress-testing scenarios.
- Include currency risk analysis (CHF vs EUR/USD).
- Extend with real-time market data feeds.

## License
MIT License

