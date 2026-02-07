# Blinkit sales performance using ML
Machine learning project to analyze the impact of marketing spend on sales performance.
# Predicting Sales Performance for Blinkit Marketing

## Problem Statement
Blinkit invests heavily in marketing campaigns, but without data-driven optimization,
marketing spend can lead to inefficient ROI. This project builds a machine learning
model to analyze how marketing expenditure impacts sales performance.

## Solution Overview
- Cleaned and preprocessed historical marketing and sales data
- Engineered time-based features to capture seasonality
- Built an end-to-end ML pipeline using scikit-learn
- Trained and optimized a Random Forest Regressor using GridSearchCV
- Evaluated performance using MAE, RMSE, and R² metrics

## Key Insights
- Marketing spend shows strong correlation with revenue
- Seasonality significantly affects sales outcomes
- Random Forest handled non-linear relationships better than linear models

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## Project Structure
```
blinkit-sales-performance-ml/
├── data/
│   └── sample_data.csv        # https://www.kaggle.com/datasets/akxiit/blinkit-sales-dataset.
├── notebooks/
│   └── eda_and_modeling.ipynb
├── src/
│   ├── preprocess.py
│   ├── train.py
│   └── evaluate.py
├── requirements.txt
├── README.md
└── .gitignore
```

