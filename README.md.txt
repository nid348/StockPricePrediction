Stock Price Prediction

This project predicts stock prices using both time series and machine learning techniques. It compares the performance of ARIMA and Gradient Boosting Regressor on historical stock data.

Tech Stack :
Python
Pandas, NumPy
Matplotlib, Seaborn
Statsmodels (ARIMA)
Scikit-learn
yFinance

Approach
Collected historical stock data (Yahoo Finance)
Performed data cleaning and EDA
Engineered features (returns, moving averages, volatility, lags)

Trained:
ARIMA (5,1,0) for time series forecasting
Gradient Boosting Regressor for supervised learning
Evaluated using RMSE, MAE, MAPE

Results
Gradient Boosting captures non-linear patterns better, while ARIMA models time dependencies effectively. Performance comparison is generated during execution.

How to Run
pip install yfinance statsmodels scikit-learn matplotlib seaborn

Open and run:

StockPrediction.ipynb

Note: For educational purposes only — not intended for financial decision-making.