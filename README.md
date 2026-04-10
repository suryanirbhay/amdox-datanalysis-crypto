# 📈 Amdox Time Series Analysis with Cryptocurrency

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.9+-blue.svg" />
  <img src="https://img.shields.io/badge/Streamlit-Dashboard-red.svg" />
  <img src="https://img.shields.io/badge/ML-LSTM%20%7C%20ARIMA%20%7C%20Prophet-green.svg" />
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" />
</p>

---

## 🔍 About The Project

This project focuses on analyzing cryptocurrency price trends using **time series forecasting techniques**. By leveraging data analytics, statistical modeling, and machine learning, the system predicts future price movements based on historical data.

It is particularly valuable for **traders, investors, and researchers** looking to gain data-driven insights into cryptocurrency price behavior.

---

## ✨ Features

| # | Feature | Description |
|---|---------|-------------|
| 1 | 📡 **Data Collection** | Real-time & historical data from CoinGecko, Binance, Yahoo Finance |
| 2 | 🧹 **Data Preprocessing** | Cleans data, handles missing values using Pandas, Matplotlib, Seaborn |
| 3 | 🤖 **Forecasting Models** | ARIMA, LSTM, and Facebook Prophet for price prediction |
| 4 | 📊 **Interactive Dashboard** | Streamlit/Plotly GUI with charts, trends & predictions |
| 5 | 📰 **Sentiment Analysis** | NLP-based analysis from crypto news & social media |
| 6 | 💹 **Real-World Applications** | Trend insights, risk assessments & price predictions |

---

## 🛠️ Tech Stack

- **Language:** Python 3.9+
- **Models:** ARIMA · LSTM · Facebook Prophet
- **Dashboard:** Streamlit · Plotly
- **Data APIs:** CoinGecko · Binance · Yahoo Finance
- **Libraries:** Pandas · NumPy · Matplotlib · Seaborn · TensorFlow/Keras · Scikit-learn

---

## 📁 Project Structure

```
amdox-crypto/
│
├── app.py                  # Main Streamlit dashboard
├── data_collection.py      # API data fetching (CoinGecko, Binance)
├── preprocessing.py        # Data cleaning & feature engineering
├── arima_model.py          # ARIMA forecasting model
├── lstm_model.py           # LSTM deep learning model
├── prophet_model.py        # Facebook Prophet model
├── sentiment_analysis.py   # NLP sentiment from news/social media
├── analytics.py            # Analytics & visualization
├── data.csv                # Sample historical crypto data
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
```

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/suryanirbhay/amdox-datanalysis-crypto.git
cd amdox-datanalysis-crypto
```

### 2. Create Virtual Environment
```bash
python -m venv .venv
.venv\Scripts\activate      # Windows
source .venv/bin/activate   # Mac/Linux
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the App
```bash
streamlit run app.py
```

### 5. Open in Browser
```
http://localhost:8501
```

---

## 📊 Models Used

### 🔵 ARIMA (AutoRegressive Integrated Moving Average)
- Best for **linear & stationary** time series
- Great for short-term predictions

### 🟢 LSTM (Long Short-Term Memory)
- Deep learning model for **complex patterns**
- Best for **non-linear** price movements

### 🟡 Facebook Prophet
- Handles **seasonality & trends** automatically
- Great for **long-term** forecasting

---

## 📸 Dashboard Preview

```
┌─────────────────────────────────────────┐
│       Crypto Price Dashboard 📈         │
├─────────────────────────────────────────┤
│  Select Coin:  [Bitcoin ▼]              │
│  Select Model: [LSTM    ▼]              │
│  Forecast Days: [30     ▼]              │
├─────────────────────────────────────────┤
│  📊 Price Chart   📉 Prediction Chart   │
│  📰 Sentiment     📈 Volatility         │
└─────────────────────────────────────────┘
```

---

## 📦 Requirements

```txt
streamlit
pandas
numpy
matplotlib
seaborn
scikit-learn
tensorflow
statsmodels
prophet
plotly
yfinance
requests
```



## 📄 License

This project is licensed under the **MIT License**.

---

<p align="center">Made with ❤️ by Amdox Team</p>
