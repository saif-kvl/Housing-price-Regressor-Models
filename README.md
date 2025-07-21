
# 🏡 Housing Price Prediction — Multi-Model Regression Project

This project demonstrates the application of various regression models on a single housing dataset to predict house prices. The goal is to compare performance across different models and understand their behavior on the same dataset.

## 📊 Models Implemented:

* **Linear Regression**
* **Ridge Regression**
* **Lasso Regression**
* **Decision Tree Regressor**
* **Random Forest Regressor**
* **Gradient Boosting Regressor**
* **XGBoost Regressor** *(optional based on usage)*
* **Support Vector Regressor**
* **K-Nearest Neighbors Regressor**

---

## 🛠️ Project Workflow:

1. **Data Loading & Exploration**

   * Data cleaning, missing value treatment, encoding categorical variables.
   * Exploratory Data Analysis (EDA) with visualizations.
2. **Feature Engineering**

   * Feature selection based on correlation.
   * Scaling and transformation.
3. **Model Building**

   * Training all regression models.
   * Hyperparameter tuning with GridSearchCV or RandomizedSearchCV.
4. **Model Evaluation**

   * Metrics Used:

     * Mean Absolute Error (MAE)
     * Mean Squared Error (MSE)
     * Root Mean Squared Error (RMSE)
     * R² Score
   * Comparison of all models' performance on test data.
5. **Result Visualization**

   * Actual vs Predicted plots.
   * Error analysis graphs.

---

## 📝 Conclusion:

This project gives insights into how different regression models perform on the same dataset.
Helps in understanding the impact of overfitting, regularization, and ensemble learning techniques in regression problems.

---

## 💻 Tech Stack:

* Python
* Pandas
* Scikit-Learn
* Xgboost, Lightgbm
* VS code 

---

## 📂 How to Run:

```bash
git clone https://github.com/yourusername/housing-regression-project.git  
cd housing-regression-project  
Open and run `housing_regression_models.py` in vs code 
```

---
