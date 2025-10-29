# Attrition ML Project

Predicting employee attrition using machine learning on a HR dataset.

## Overview
- **Goal**: Build a model to predict if an employee will leave the company.
- **Dataset**: Employee features like age, job satisfaction, monthly income, etc.
- **Tools**: Python, Pandas, Scikit-learn, SHAP for interpretability.

## Files
- `Attrition_Data_Preprocessed.ipynb`: Data cleaning, encoding, and feature engineering.
- `Attrition_Data_Preprocessed.csv`: Processed dataset.
- `Attrition_Model_Training.ipynb`: Model building (Logistic Regression, ensembles), evaluation, and SHAP analysis.
- 'attrition_final_blended_model.pkl': Saved Best Model.
- 'Attrition_Test_Data_Preprocessed_and_Tested.ipynb': Testing on unseen data.
- 'attrition_test_predictions_final.csv': Final predicted output on unseen data with Employee ID, Attrition, Probability and Risk Category.

## How to Run
1. Clone: `git clone https://github.com/rajumanojkumar/attrition-ml-project.git`
2. Install deps: `pip install -r requirements.txt`
3. Run notebooks in Jupyter.

## Results
- Best Model: Blended Model (Accuracy = 0.92, F1 Score = 0.87).
- Key Insights: Overtime, MonthlyIncome and TravelProfile strongly predict attrition.
