# Medical Insurance Cost Prediction

## Overview

This project predicts individual medical insurance charges using machine learning regression. It combines comprehensive data exploration, targeted feature engineering, systematic preprocessing and rigorous model selection to yield robust, actionable and interpretable results—essential in high-stakes healthcare analytics.

***

## 1. Project Workflow

### **Exploratory Data Analysis (EDA)**
- Explored feature relationships identifying **smoking status, age and BMI** as major drivers of costs.
- Discovered significant non-linear patterns and skewness in medical charges, guiding all subsequent modeling decisions.

### **Feature Engineering**
- Crafted enhanced features, such as **BMI categories** and important **interaction terms** (e.g. smoker × age), to amplify predictive signal and capture complex patterns.

### **Preprocessing**
- Applied a **log transformation** to the target variable to mitigate skewness and stabilize variance, addressing heteroscedasticity.
- Utilized reproducible preprocessing pipelines for scaling and encoding, ensuring consistency and reliability.

### **Model Building & Optimization**
- Benchmarked a range of regression algorithms—linear, tree-based and kernel methods.
- Applied **k-fold cross-validation** for thorough model validation.
- Performed **hyperparameter tuning** to extract maximum performance from top models.

***

## 2. Results

- The **Support Vector Regressor (SVR)**, after targeted tuning, delivered top predictive accuracy, explaining nearly 89% of the variance in medical charges (R² = 0.8884).
- Thoughtful feature engineering and data transformations were crucial for capturing meaningful relationships.
- SVR surpassed other regression techniques, modeling both linear effects and complex interactions in the data.

***

## 3. Key Insights

- **Domain-informed feature design** and transformation dramatically improved model performance and trustworthiness.
- A structured, modular pipeline enabled reproducibility, reliability and scalability across all stages.
- Careful model selection and tuning produced a solution that generalizes well and respects the complexity of real-world insurance costs.
- **Interpretability:** Feature choices and clear modeling logic ensure results are transparent and explainable—a critical requirement in regulated healthcare and insurance contexts.

***

## 4. Summary Statement

*This project demonstrates expertise in harnessing data-driven insights for medical insurance analytics—delivering a robust, transparent and high-performance machine learning solution that balances accuracy, interpretability and practical relevance.*
