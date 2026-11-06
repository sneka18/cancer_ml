# Breast Cancer Diagnosis — ML Classification Project

## Project overview
A beginner-friendly supervised machine-learning project that predicts a binary label (`benign` or `malignant`) from numeric measurements in the Wisconsin Diagnostic Breast Cancer dataset.

**Important:** This is an educational exercise only. It is not a medical diagnostic tool.

## Files
- `ML_Project.ipynb` — step-by-step Jupyter Notebook
- `breast_cancer_dataset.csv` — dataset used by the notebook
- `Summary_Report.pdf` — methodology, metrics, visualizations and conclusion
- `outputs/` — generated model comparison table and visualizations

## Requirements
- Python 3.9 or later
- Jupyter Notebook or JupyterLab
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Setup and run (Windows)
1. Extract the ZIP file.
2. Open Command Prompt or PowerShell in the extracted project folder.
3. (Recommended) Create a virtual environment:
   ```bash
   python -m venv .venv
   .venv\\Scripts\\activate
   ```
4. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```
5. Start Jupyter:
   ```bash
   jupyter notebook
   ```
6. Open `ML_Project.ipynb` and run all cells from top to bottom.

Keep `breast_cancer_dataset.csv` in the same folder as the notebook.

## Workflow covered
- Dataset inspection and missing-value checks
- Target encoding
- Class distribution and outlier visualization
- Stratified train-test split
- Median imputation
- Feature scaling for Logistic Regression
- Feature selection using SelectKBest
- Logistic Regression, Random Forest and Gradient Boosting
- Accuracy, precision, recall, F1 score and ROC-AUC
- Confusion matrix and ROC curve visualization

## Notes
- The provided dataset contains no missing values; imputation is retained in pipelines as a robust preprocessing step.
- Outliers are inspected but not automatically removed because extreme values may be meaningful.
- Preprocessing steps are fitted within pipelines to reduce data leakage.
