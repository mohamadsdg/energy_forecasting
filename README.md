# Household Energy Consumption Forecasting

Machine Learning Fundamentals - Practical Skills Assessment.

Forecasts next-hour household electric power consumption using the [Individual Household Electric Power Consumption dataset](https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption) (UCI Machine Learning Repository).

## Contents

`energy_forecasting.ipynb` covers:

1. Data loading and preprocessing (missing values, datetime indexing, gap filling, hourly resampling, feature engineering)
2. Exploratory data analysis
3. Chronological train/test split
4. One-step-ahead forecasting models: naive baseline, SARIMA, Linear Regression, Random Forest, XGBoost
5. Model evaluation and comparison

## Requirements

- Python 3
- numpy, pandas, matplotlib, seaborn
- statsmodels
- scikit-learn
- xgboost

## Usage

Open and run `energy_forecasting.ipynb` in Jupyter.
