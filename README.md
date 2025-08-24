# 📈 Algorithmic Trading Simulation – ICICI Bank (SMA Strategy)

This project implements a **moving average crossover strategy** (SMA 50/200) on **ICICI Bank stock data** from NSE. It covers **data cleaning, signal generation, backtesting with transaction costs, and risk evaluation**.

---

## 🚀 Overview
- **Dataset**: ICICIBANK.csv (NSE data from Kaggle)  
- **Strategy**: Long when SMA(50) > SMA(200), exit when SMA(50) < SMA(200)  
- **Backtest**: Includes 0.1% transaction costs, compares vs buy-and-hold  
- **Metrics**: CAGR, Sharpe Ratio, Max Drawdown, Win Rate  
- **Validation**: Train/Test split + parameter grid search  

---

## ⚙️ Setup
```bash
git clone https://github.com/yourusername/quant-trading-sma.git
cd quant-trading-sma
pip install -r requirements.txt
jupyter notebook notebooks/icicibank_sma.ipynb
