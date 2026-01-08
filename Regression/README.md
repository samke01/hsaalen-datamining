# Football Player Value Prediction

## Data Mining & Machine Learning – Regression Project

## Overview

This repository contains a regression-based data mining project focused on **predicting football player market values** using supervised machine learning techniques.  
The project was developed as part of the *Data Mining & Machine Learning* course (Regression – Part 2, Case 2).

The workflow follows a typical end-to-end data science pipeline:

- Data understanding and cleaning  
- Model comparison  
- Model optimization and evaluation  

Both **Jupyter notebooks** and **HTML exports** are provided to ensure full reproducibility and easy inspection of results without requiring code execution.

---

## Project Structure

```
├── Regression_Data_Cleaning.ipynb
├── Regression_Data_Cleaning.html
├── Regression_Model_Comparisson.ipynb
├── Regression_Model_Comparisson.html
├── Regression_Modelling_Optimized.ipynb
├── Regression_Modelling_Optimized.html
├── football-prediction.ipynb
└── README.md
```

## Notebooks

### 1) Regression_Data_Cleaning
**Goal:** Prepare the dataset for regression modeling.

Includes:
- Dataset exploration and feature overview  
- Missing value analysis and recurring missingness patterns  
- Identification of high-missing feature blocks  
- Decisions on feature retention vs. imputation strategy  

---

### 2) Regression_Model_Comparisson
**Goal:** Compare baseline regression models.

Includes:
- Baseline comparison (focus on tree-based models)  
- Random Forest Regressor vs. XGBoost Regressor  
- Evaluation using standard regression metrics:
  - MSE
  - MAE
  - RMSE
  - R²
- Feature importance inspection and comparison  

---

### 3) Regression_Modelling_Optimized
**Goal:** Optimize the selected regression model.

Includes:
- Refined preprocessing experiments  
- Feature selection variants (e.g., correlation reduction)  
- Hyperparameter search and best-parameter selection  
- Train vs. test evaluation tables and final performance review  

---

### 4) football-prediction.ipynb
**Goal:** Project-level notebook integrating the regression workflow and results.

---

## How to Use

### Option A: View results only
Open the `.html` files in your browser to inspect:
- data cleaning decisions  
- model comparison outputs  
- evaluation tables and plots  

### Option B: Run notebooks locally
1. Open the repository in Jupyter Notebook / JupyterLab
2. Run the notebooks in this order:
   1. `Regression_Data_Cleaning.ipynb`
   2. `Regression_Model_Comparisson.ipynb`
   3. `Regression_Modelling_Optimized.ipynb`

> Note: There is no `requirements.txt` in this repository. If you run the notebooks locally, install the needed Python packages as prompted by import errors (commonly: `pandas`, `numpy`, `scikit-learn`, `xgboost`, `matplotlib`).

---

## Notes on Repository History

The notebooks were completed in **June 2024**. Some notebooks were initially missing from the GitHub repository and were later **restored** to ensure completeness and reproducibility.

---

## License / Usage

Created for **academic purposes**. Reuse is allowed for learning and non-commercial use with appropriate attribution.
