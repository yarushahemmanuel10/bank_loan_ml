# Bank Loan Default Prediction

## Overview
This project predicts the likelihood of a bank client defaulting on a loan using machine learning techniques. The dataset contains client demographics, employment, income, and loan purpose information. The target variable is `debt` (loan default status).

## Dataset
- **Records:** 21,525  
- **Features:** `children`, `days_employed`, `dob_years`, `education`, `education_id`, `family_status`, `family_status_id`, `gender`, `income_type`, `debt`, `total_income`, `purpose`, `purpose_short`  

## Objectives
- Clean and preprocess the dataset  
- Handle missing and incorrect values  
- Standardize categorical features  
- Prepare data for machine learning models  

## Data Cleaning & Preprocessing
1. **Negative Values:** Corrected `children` and `days_employed` using absolute values.  
2. **Categorical Standardization:** Converted `education` to lowercase and simplified `purpose`.  
3. **Missing Values:** Imputed `days_employed` and `total_income` using median values grouped by `education` and `income_type`.  
4. **Outliers & Unusual Values:** Corrected unrealistic ages, employment days, and children counts.  

## Exploratory Data Analysis (EDA)
- Checked feature distributions and correlations with `debt`.  
- Ensured clean categorical variables and identified rare/edge cases.

## Tools & Libraries
- Python 3.x  
- Pandas  
- NumPy  
- Jupyter Notebook  

## How to Run
1. Clone the repository.  
2. Open `Practical_work.ipynb` in Jupyter Notebook.  
3. Follow the notebook for data cleaning, preprocessing, and analysis.

## Next Steps
- Encode categorical variables for ML models  
- Train classifiers like Logistic Regression, Random Forest, or SVM  
- Evaluate using accuracy, precision, recall, and F1-score  

## Author
**Yarushah E Sardar**  
Mini project on practical machine learning methods.
