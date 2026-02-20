**Retail Sales Forecasting — SARIMA vs LSTM**
**Objective**

Forecast monthly retail sales using classical time-series modeling (SARIMA) and deep learning (LSTM), and compare predictive performance for business decision support.

**Dataset**

Monthly car sales dataset

108 observations

Strong trend + yearly seasonality

**Methodology**

Exploratory Data Analysis

Stationarity testing (ADF Test)

SARIMA modeling

LSTM sequence modeling

Model evaluation (MAE, RMSE, MAPE)

Business impact analysis

**Model Performance**
Model	MAE	RMSE	MAPE
SARIMA	1819	2334	~12.5%
LSTM	1318	1691	~9%

✔ LSTM achieved ~27% improvement in forecasting accuracy.

**Business Impact**

Reduced forecasting error by ~500 units per month

Improved inventory planning accuracy

Demonstrates value of deep learning in demand forecasting

**Tech Stack**

Python

Pandas

Statsmodels

TensorFlow / Keras

Scikit-learn

Matplotlib

**Future Improvements**

Add exogenous variables (promotions, macro factors)

Implement rolling forecast validation

Deploy via Streamlit dashboard
