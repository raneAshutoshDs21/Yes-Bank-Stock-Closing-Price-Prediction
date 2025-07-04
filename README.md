# 📈 YES BANK Stock Closing Price Prediction

This project focuses on **predicting the closing price of YES BANK stock** using historical financial data and supervised machine learning models. The objective is to build a robust regression-based pipeline to help forecast future stock prices for investment planning and risk assessment.

## 🧠 Project Type

Supervised Machine Learning – **Regression Problem**

---

## 📌 Problem Statement

Predicting stock prices is a critical and challenging task due to the influence of numerous market factors, including economic events and company-specific incidents (like the 2018 YES Bank fraud case). This project aims to build predictive models to estimate the closing stock price using historical financial indicators.

---

## 🧾 Dataset Description

The dataset contains the following key columns:

- `Date`
- `Open`
- `High`
- `Low`
- `Close` (Target variable)

Data Source: [Yahoo Finance / Kaggle / Other] *(Add the actual data source)*

---

## ⚙️ Workflow Summary

### 🔹 1. Data Cleaning & Preprocessing
- Outlier removal using **Interquartile Range (IQR)**
- Handled **skewness** using log transformation
- **Feature scaling** with StandardScaler
- Splitting dataset: **80% training / 20% testing**

### 🔹 2. Models Implemented
- **Linear Regression**
- **Decision Tree Regressor (DTR)**
- **XGBoost Regressor (XGBR)**

### 🔹 3. Hyperparameter Tuning
Performed both **GridSearchCV** and manual tuning for:
- DTR: `max_depth`, `min_samples_split`, `min_samples_leaf`
- XGBR: `learning_rate`, `n_estimators`, `max_depth`, `subsample`, `colsample_bytree`

---

## 📊 Evaluation Metrics

Models were evaluated using standard regression metrics:
- ✅ R² Score
- 📉 Mean Absolute Error (MAE)
- 📉 Mean Squared Error (MSE)

---

## 📈 Visualizations

The notebook includes:
- Stock trend line plots
- Feature importance plots (XGBoost)
- Residual analysis
- Model performance comparisons

---

## 🧰 Tech Stack

| Tool / Library     | Use                             |
|--------------------|----------------------------------|
| Python             | Programming language             |
| Pandas, NumPy      | Data manipulation                |
| Matplotlib, Seaborn| Data visualization               |
| Scikit-learn       | ML models, preprocessing         |
| XGBoost            | Gradient Boosting Regressor      |
| Jupyter Notebook   | Interactive development          |

---

## 🗂️ File Structure

📁 Yes-Bank-Stock-Prediction/
│
├── 📄 Yes Bank Stock Prediction.ipynb # Main Jupyter notebook
├── 📄 README.md # Project overview
