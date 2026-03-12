# 📈 Retail Sales Forecasting using Time Series Analysis

This project focuses on predicting future retail sales using historical data and time-series forecasting techniques. The analysis explores trends, seasonality, holiday effects, and promotional impacts on sales before building a forecasting model using ARIMA.

---

# 📊 Project Overview

Retail businesses rely heavily on accurate sales forecasting for inventory planning, demand management, and promotional strategies. This project analyzes Walmart retail sales data to identify patterns and predict future sales using statistical time-series models.

The project includes:

- Exploratory Data Analysis (EDA)
- Trend and Seasonal Pattern Analysis
- Holiday Impact Analysis
- Promotional Impact Analysis
- ARIMA Time-Series Forecasting
- Forecast vs Actual Sales Comparison
- Model Performance Evaluation

---

# 🗂 Dataset

The dataset used in this project includes three main files:

- **train.csv** → Historical weekly sales data
- **features.csv** → Economic indicators and promotional markdowns
- **stores.csv** → Store type and size information

Key variables used:

- Weekly Sales
- Holiday Indicator
- Promotional Markdown values
- Fuel Price
- CPI (Consumer Price Index)
- Unemployment Rate

---

# ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- Scikit-learn
- Jupyter Notebook

---

# 🔍 Exploratory Data Analysis

The analysis investigates:

- Overall sales trends
- Seasonal patterns across weeks
- Impact of holidays on sales
- Effect of promotional markdowns

Visualizations include:

- Sales trend over time
- Seasonal decomposition
- Holiday vs non-holiday sales comparison
- Promotion vs sales relationship

---

# 📉 Time Series Forecasting

An **ARIMA (AutoRegressive Integrated Moving Average)** model was used to forecast future sales based on historical patterns.

Steps involved:

1. Data preprocessing and aggregation
2. Time-series decomposition
3. Train-test split
4. Model training using ARIMA
5. Sales forecasting
6. Forecast vs actual comparison

---

# 📊 Model Evaluation

The forecasting model was evaluated using:

- **MAE (Mean Absolute Error)**
- **RMSE (Root Mean Squared Error)**

These metrics measure the difference between predicted and actual sales values.

---

# 📌 Key Insights

- Holiday weeks show significantly higher sales.
- Promotional markdowns influence customer purchasing behavior.
- Sales demonstrate clear seasonal patterns.
- Time-series models can effectively capture retail demand patterns.

---

# 🚀 Future Improvements

Possible improvements for this project include:

- Using **Facebook Prophet** for forecasting
- Implementing **LSTM deep learning models**
- Store-level sales forecasting
- Hyperparameter tuning for ARIMA

