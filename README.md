# stocks_ML

## Overview
`stocks_ML` is a Python-based project that uses TensorFlow and Long Short-Term Memory (LSTM) neural networks to analyze stock time series data. The model is designed to predict which stocks are likely to perform well on the next day based on the previous day's data. **This project does not provide financial advice or recommendations for buying or selling stocks.** It is intended for educational and research purposes only.

## Features
- Utilizes LSTM networks for time series forecasting.
- Input: Historical stock data (previous day's data points such as open, close, high, low, volume).
- Output: Probability scores indicating which stocks are likely to perform well on the next day.
- Performance evaluation using standard metrics like accuracy, precision, recall, and ROC-AUC curve.
  
## Technologies
- **Python 3.x**
- **TensorFlow 2.x**
- **Pandas, NumPy** for data manipulation.
- **Matplotlib** for data visualization and result plotting.
- **yfinance** for downloading stock data.

## Installation
To get started, clone the repository and install the required dependencies:

```bash
git clone https://github.com/noahhood/stocks_ML.git
cd stocks_ML
pip install -r requirements.txt