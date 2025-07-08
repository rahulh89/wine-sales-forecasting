# Time Series Forecasting – Wine Sales

This project involves time series forecasting on two types of wine sales data – Sparkling and Rose wine – from 1980 to 1995.

## Contents
- 📁 `report/` – Project report (PDF)
- 📁 `data/` – Raw datasets
- 📁 `notebooks/` – Code for preprocessing, modeling, and forecasting
- 📁 `output/` – Model results and charts

## Models Used
- Naive, Simple & Moving Average
- Exponential Smoothing (SES, DES, TES)
- ARIMA & SARIMA (auto/manual)

## Tools & Libraries
- Python (pandas, statsmodels, matplotlib)
- Jupyter Notebook


---

## 🧠 Problem Statement

As a data analyst at **ABC Estate Wines**, your task is to:
- Analyze historical sales data for two wine products.
- Build and compare multiple forecasting models.
- Predict the next 12 months of sales and make business recommendations.

---

## 🧪 Methodology

### Models Implemented:
- **Naïve Forecast**
- **Simple Average**
- **Moving Average (2pt, 4pt, 6pt, 9pt)**
- **Simple Exponential Smoothing (SES)**
- **Double Exponential Smoothing (DES – Holt’s Model)**
- **Triple Exponential Smoothing (TES – Holt-Winters Model)**
- **ARIMA / SARIMA (Auto & Manual Tuning)**

### Evaluation Metrics:
- **RMSE (Root Mean Squared Error)**
- **MAPE (Mean Absolute Percentage Error)**

---

## 🔧 Tools & Technologies
- **Python 3.x**
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `statsmodels`
- Jupyter Notebook

---

## 📈 Key Insights
- **Sparkling Wine** showed stronger seasonal trends.
- **2-point Moving Average** performed best for Rose.
- **SARIMA with seasonal tuning** provided best results for Sparkling.

---

## 🗨 Recommendations
- Use **seasonality-aware models** for Sparkling Wine.
- Maintain minimal stock of Rose during off-season.
- Use 12-month forecasts for capacity and inventory planning.
