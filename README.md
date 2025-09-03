# 🚗 Vehicle Coupon Recommendation Prediction

## 📌 Project Overview
This project explores the **Vehicle Coupon Recommendation Dataset** with the objective of predicting whether a customer will accept a coupon offer based on their demographics, context, and trip details.  

The project involves **data cleaning, feature engineering, exploratory data analysis (EDA), and machine learning modeling** to build a recommendation model.

---

## 🎯 Problem Statement
Businesses want to **maximize coupon redemption rates** by targeting the right customers at the right time.  
The goal is to analyze customer behavior and build a predictive model that determines whether a customer will **accept or reject a coupon**.

---

## 📊 Dataset
- **Source**: [UCI Machine Learning Repository – In-Vehicle Coupon Recommendation Dataset](https://archive.ics.uci.edu/ml/datasets/in-vehicle+coupon+recommendation)  
- **Rows**: ~12,000  
- **Features**: Demographics, trip details, weather, time, passenger type, income, occupation, etc.  
- **Target**: Whether a coupon was accepted (`Y/N`).  

---

## 🛠️ Methodology

1. **Data Understanding**
   - Explored dataset shape, missing values, and feature types.
   - Reviewed distributions and feature summaries.

2. **Data Preparation**
   - Handled missing values with mode imputation.
   - Removed duplicates.
   - Standardized categorical feature names.
   - Created **age buckets, occupation groups, and income categories**.

3. **Exploratory Data Analysis (EDA)**
   - Visualized coupon acceptance patterns across demographics and trip contexts.
   - Identified factors strongly associated with acceptance.

4. **Modeling**
   - Applied **Logistic Regression** and **Random Forest Classifier**.
   - Performed hyperparameter tuning with GridSearchCV.
   - Evaluated with train-test split and cross-validation.

5. **Evaluation**
   - **Random Forest achieved ~72% accuracy**, outperforming Logistic Regression.

---

## 📦 Tech Stack
- **Programming**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Environment**: Jupyter Notebook  

---

## 📈 Key Insights
- Younger age groups and higher-income individuals showed higher coupon acceptance.  
- Contextual features (e.g., weather, time of day, passenger type) influenced redemption likelihood.  
- Random Forest provided the best performance, suggesting non-linear interactions are important.  

---

## ▶️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/vehicle-coupon-recommendation.git
   cd vehicle-coupon-recommendation
