# ☀️ Solar Radiation ML Models – Saudi Arabian Dataset

This repository contains the full machine learning workflow to predict Global Horizontal Irradiance (GHI) using Saudi Arabia’s weather data (2015–2020).

## 🔍 Objectives
- Train & compare multiple ML models (Linear Regression, RF, XGB, etc.)
- Evaluate with MAE, RMSE, R²
- Export best model for deployment

## 🧪 Models Evaluated
- Linear Regression ✅
- Random Forest
- XGBoost
- Histogram Gradient Boosting
- Support Vector Regression
- Artificial Neural Networks
- Decision Tree
- KNN

## 📁 Contents
- `notebooks/`: Model training and evaluation
- `models/`: Saved `.pkl` files
- `dataset/`: Cleaned sample dataset
- `requirements.txt`: Library dependencies

## 📌 Highlights
- Best R²: 0.97 (Linear Regression)
- 21 input features including DHI, DNI, humidity, wind speed
- 10-fold and 43-fold cross-validation

## 🔗 Live App (Deployed Model)
See deployment repo here: [link to your Render deployment repo]

🔗 **Related Repositories**:
- 🔬 [Model Training & Evaluation Repo](https://github.com/nishnarudkar/solar-radiation-ml-models)
- 🌐 [Web App Deployment Repo](https://github.com/nishnarudkar/Solar-Radiation-Prediction-using-Saudi-Arabia-Dataset)


