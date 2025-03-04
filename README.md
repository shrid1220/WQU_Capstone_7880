# WQU_Capstone

# Machine Learning and Deep Learning Investment Strategies

## 📌 Project Overview
This project evaluates machine learning and deep learning models for stock market prediction. It integrates technical indicators, historical price data, and advanced ML/DL techniques to develop and backtest trading strategies across developed, emerging, and frontier markets.

## 📊 Features
- **Data Collection:**
  - Uses Yahoo Finance and other APIs to fetch stock market data.
  - Covers global markets: S&P 500, DAX, FTSE 100, VNINDEX, BET, etc.
  
- **Feature Engineering:**
  - Implements RSI, MACD, Bollinger Bands, VWAP, Ichimoku Cloud, and over 100+ technical indicators.
  - Uses Fourier Transform and statistical features to enhance signal extraction.
  
- **Machine Learning Models:**
  - Traditional ML: Logistic Regression, SVM, Decision Trees, Random Forest, XGBoost, LightGBM.
  - Deep Learning: LSTMs, GRUs, CNNs, Transformers, GANs, Hybrid Models (CNN-LSTM, CNN-Transformer).
  
- **Backtesting & Validation:**
  - Combinatorial Purged Cross-Validation (CPCV) ensures robustness.
  - Sharpe Ratio, Sortino Ratio, Maximum Drawdown used for strategy evaluation.

- **Trading Signal Generation & Strategy Development:**
  - Translates predictions into buy/sell signals.
  - Compares different ML/DL-based strategies with buy-and-hold benchmarks.

## 🛠 Installation & Dependencies
1. **Clone the repository:**
   ```bash
   git clone (https://github.com/shrid1220/WQU_Capstone.git)
   cd WQU_Capstone
   ```

2. **Install required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up Yahoo Finance API (if needed):**
   - Some data fetching functions may require installation.

## 📂 Project Structure
```
├── Codebase/ # Jupyter Notebooks for EDA & Modeling & ML/DL models.
├── Dataset/ # Historical Market Data
├── Output/ # Backtesting Output Comparison
├── Result/ # Results w.r.t Accuracy , Return , Trading
├── 📝 Capstone_Paper.pdf # Research Paper
├── README.md                 # Project documentation
├── requirements.txt          # Required dependencies
├── LICENSE                   # License information
```


## 📊 Results
- **Key Findings:**
  - Deep Learning models (LSTM, GRU, Transformers) showed superior performance over traditional ML models.
  - CPCV enhanced robustness by reducing lookahead bias.
  - Hybrid CNN-LSTM and CNN-Transformer models demonstrated the best generalization across different market conditions.
  
- **Trading Strategy Performance:**
  - Compared ML/DL-based signals with a buy-and-hold benchmark.
  - Evaluated profitability using Sharpe Ratio, Sortino Ratio, and Maximum Drawdown.




## **Contributors:**
-   Dachawar Shrinivas Kamalkishor (shrid12@yahoo.com).
-   Mai Duc Toan (maiductoan130298@gmail.com).
-   Assem Atallah (assembassel@gmail.com).
