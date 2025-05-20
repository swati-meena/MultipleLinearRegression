# 📊 Predicting Profit Based on Business Spendings (MLR with OLS)

This project explores how different categories of spending affect company profit using Multiple Linear Regression (MLR) and statistical feature selection (OLS with p-values).

## 🚀 Objective
To determine which among **Digital Marketing**, **Promotion**, and **Research** contributes most to profit, helping companies optimize their budgets.

## 🧰 Tools & Libraries
- Python (Pandas, Numpy, Seaborn, Matplotlib)
- scikit-learn
- statsmodels

## 📈 Methodology
1. **Exploratory Data Analysis**
2. **Feature Engineering (Dummy Encoding)**
3. **Model Building** using scikit-learn LinearRegression
4. **Statistical Inference** using statsmodels.OLS
5. **Feature Selection** with Backward Elimination
6. **Evaluation** using R², MAE, MSE, and plots

## 📊 Key Insights
- Research spend was found to have the strongest positive impact.
- Promotion showed little to no significance in profit prediction.
- R² of ~95% indicates strong model fit.

## 📸 Visuals

![Actual vs Predicted](images/actual_vs_predicted.png)

## 📁 Dataset
The dataset contains columns:
- `DigitalMarketing`
- `Promotion`
- `Research`
- `State` (categorical)
- `Profit` (target)

## 🤝 Let's Connect
If this project interests you, feel free to connect or reach out!

---
