# Free Cash Flow Prediction using Regression Models

This project demonstrates a machine learning approach to predict **Free Cash Flow (FCF)** of companies using key financial indicators. The dataset consists of annual financial data for 604 companies, with 8 selected features from the Income Statement, Cash Flow, and Balance Sheet: Capital Expenditure, EBITDA, Total Debt, Total Revenue, Working Capital, Accounts Receivable, Accounts Payable, and Cash & Cash Equivalents.

## Methodology
- Preprocessing: Normalized features using **MinMaxScaler**, replaced null values with 0, and removed samples with missing target values.
- Data Split: 90% training, 10% testing.
- Models Used: **Linear Regression**, **Ridge Regression**, **Polynomial Regression**, and **Random Forest Regressor**.
- Evaluation Metrics: **Mean Absolute Error (MAE)** and **Root Mean Squared Error (RMSE)**.

## Challenges and Limitations
- Limited dataset size (2,400 samples) and insufficient online data.
- Financial results affected by external factors not included in the features.
- Minimal hyperparameter tuning and training epochs.

This project highlights the potential of regression models to predict FCF from basic financial metrics and serves as a baseline for further experiments with larger and more comprehensive datasets.