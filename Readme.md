# Customer Churn Prediction

An end-to-end machine learning and data analytics project designed to identify and predict customer churn. This repository combines SQL-based exploratory data analysis, modular Python machine learning pipelines (Random Forest), and Power BI/DAX reporting resources.

## Project Structure

```text
├── Data/
│   └── Customer_Data.csv             # Raw customer dataset
├── src/
│   ├── data_preprocessing.py         # Data cleaning and feature engineering
│   ├── balance_data.py               # Handling class imbalance
│   └── evaluate.py                   # Model evaluation metrics
├── Codes, Queries & DAX/
│   ├── Power Query Transformations & Measures.docx
│   ├── Python Codes for Random Forest.docx
│   └── SQL Queries.docx
├── EDA and Null Values.sql           # SQL scripts for EDA and missing value checks
├── train.ipynb                       # Model training workflow
└── Churn_Prediction.ipynb            # End-to-end analysis and churn prediction
```

## Workflow Overview

1. **Exploratory Data Analysis (SQL):** Inspect data distributions, anomalies, and null values using `EDA and Null Values.sql`.
2. **Preprocessing & Balancing (Python):** Clean raw data (`src/data_preprocessing.py`) and address target class imbalance (`src/balance_data.py`).
3. **Modeling & Evaluation:** Train a Random Forest classifier (`train.ipynb`, `Churn_Prediction.ipynb`) and assess performance (`src/evaluate.py`).
4. **BI & Reporting:** Leverage Power Query transformations and DAX measures (documented in `Codes, Queries & DAX/`) for dashboard visualization.

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/prkxr/customer-churn-prediction.git
   cd customer-churn-prediction
   ```

2. **Install dependencies:**
   Ensure you have Python 3.x installed along with standard data science libraries:
   ```bash
   pip install pandas numpy scikit-learn imbalanced-learn jupyter
   ```

3. **Run the notebooks:**
   Launch Jupyter Notebook and open `train.ipynb` or `Churn_Prediction.ipynb` to execute the pipeline.