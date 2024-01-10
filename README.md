# Stock-Price-Analysis

Explore historical stock price data for PT Bank Negara Indonesia (BBNI.JK), perform thorough exploratory data analysis (EDA), implement regression models, and make predictions for future stock price trends.

## Dataset Information

### PT Bank Negara Indonesia (Persero) Tbk Stock Historical Price (BBNI.JK)

- Source: Yahoo Finance
- Time Range: January 2019 until present
- Context: This dataset contains historical stock price data for PT Bank Negara Indonesia (Persero) Tbk.

## Acknowledgements

I'd like to acknowledge the Kaggle community for providing the dataset and making it available for analysis. You can download the dataset from [this Kaggle dataset link](https://www.kaggle.com/datasets/caesarmario/bank-negara-indonesia-stock-historical-price).

## Inspiration

- Forecasting stock price after January 2019
- Implementing machine learning models.
- Perform data analysis/data visualization of historical stock prices.

## Log

- 4 January 2024: Initialization and fully automated update using Kaggle schedule run.

---

### Usage

This repository contains code and analysis related to the historical stock price data for PT Bank Negara Indonesia (BBNI.JK). You can use this repository to:

1. Perform Exploratory Data Analysis (EDA) on the historical stock price data.
2. Implement regression models to make predictions for future stock price trends.
3. Explore various data visualization techniques to gain insights into the stock price behavior.

## Analysis and Findings

The analysis involves forecasting stock prices using multiple machine learning models, specifically focusing on Linear Regression, Random Forest Regressor, and Gradient Boosting Regressor. Here's a breakdown of the analysis and its findings:

1. **Descriptive Statistics and Data Visualization:**

   - **Descriptive Statistics:** Provided a statistical overview of the Bank Negara Indonesia (BNI) stock data since January 2019, detailing key metrics like mean, standard deviation, min, and max values for 'Open', 'High', 'Low', 'Close', 'Adjusted Close', and 'Volume'.
   - **Distribution of Key Metrics:** Visualized the distribution of stock prices ('Open', 'High', 'Low', 'Close') to understand the range and common values.
   - **Correlation Matrix:** Illustrated the relationships between different stock metrics to comprehend how they influence each other.

2. **Machine Learning Models for Forecasting:**

   - **Linear Regression Model:** A basic yet powerful model used for predicting stock prices based on linear relationships between features ('Open', 'High', 'Low', 'Volume') and the target ('Close').
   - **Random Forest Regressor:** An ensemble model that uses multiple decision trees to make more accurate predictions than a single decision tree. It's effective in capturing non-linear relationships.
   - **Gradient Boosting Regressor:** Another ensemble technique that builds models sequentially, each one correcting the errors of the previous, typically leading to better accuracy.

3. **Model Evaluation and Comparison:**

   - **Mean Absolute Error (MAE):** Calculated for each model to measure the average magnitude of errors in the predictions. It's a metric to evaluate the accuracy of the models, where a lower MAE indicates better performance.
   - **Linear Regression MAE:** 21.90
   - **Random Forest MAE:** 27.32
   - **Gradient Boosting MAE:** 27.81
   - The comparison showed that the Linear Regression model performed the best based on MAE among the three models for this specific dataset.

4. **Visualization of Forecasting:**

   - A comprehensive plot compared the actual closing prices against the forecasted prices for each model.
   - This visual comparison is crucial for assessing how well each model's forecasts align with the actual stock prices.

**Summary:**

The analysis provided a multifaceted understanding of the BNI stock prices using different machine learning models. The Linear Regression model, despite its simplicity, yielded the best results in terms of MAE for this dataset. Such forecasting models are invaluable for making informed decisions in stock trading, though they should be used cautiously considering the inherent unpredictability of the stock market.


### Getting Started

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/Stock-Price-Analysis.git
