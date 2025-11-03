# home-credit-default-risk
Machine Learning project to predict loan default risk using Home Credit dataset. Includes data preprocessing, feature engineering, and model training (Random Forest, CatBoost)).

# Home Credit Default Risk

This project predicts the likelihood of loan default using multiple related datasets from Home Credit.  
It includes data cleaning, feature engineering, handling imbalanced classes, and model evaluation using AUC.

## Contents
- Data merging from multiple sources (`application`, `bureau`, `previous_application`, etc.)
- Feature engineering and aggregation
- Handling imbalanced target with SMOTE and class weights
- Model training using LightGBM
- Evaluation using AUC and precision-recall metrics

