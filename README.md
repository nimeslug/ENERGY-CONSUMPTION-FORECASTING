# Energy Consumption Forecasting with Machine Learning & Deep Learning

This project focuses on predicting building energy consumption using a wide range of machine learning and deep learning algorithms. It provides a modular framework to preprocess data, engineer features, train models, and evaluate performance.

---

## Dataset

The dataset includes timestamped energy usage data along with environmental and operational features:

- Temperature, Humidity
- Occupancy, Square Footage
- HVAC and Lighting usage (On/Off)
- Renewable energy generation
- Holiday and Weekend indicators
- Derived features (e.g., Temp × Humidity, Energy per Sqft)

---

## Models Included (and planned)

- Linear Regression  
- Random Forest Regressor  
- XGBoost, LightGBM, CatBoost  
- Support Vector Regression (SVR)  
- Naive Bayes (for classification variants)  
- K-Means (for clustering insight)  
- Artificial Neural Networks (ANN)  
- Temporal Fusion Transformer (TFT)  
- Stacking & Ensemble methods
- Decision Tree

---

## Key Features

- Clean and structured feature engineering
- Multi-model training and evaluation
- Probabilistic forecasting via quantile regression
- Metrics: MAE, RMSE, R², SMAPE, Quantile Loss
- Visual comparison of model predictions
- Real-time single-step prediction support

---

## Requirements

Install required libraries with:
```bash
pip install pandas numpy scikit-learn matplotlib
pip install xgboost lightgbm catboost
pip install pytorch-lightning==2.2.4 torchmetrics==1.3.1 pytorch-forecasting==1.4.0
