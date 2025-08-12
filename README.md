# Telco Customer Churn Analysis & Prediction

## Project Overview
This project analyzes Telco customer churn data to identify key factors influencing churn and to build a predictive model that forecasts the likelihood of a customer leaving. It combines SQL for data exploration, Python for predictive modelling, and Tableau for interactive dashboard creation.

---

## Project Contents
- **`telco_clean.csv`** – Cleaned dataset prepared for analysis.
- **`telco.db`** – SQLite database containing structured Telco data.
- **`sql_queries.py`** – Python script running SQL queries for initial data exploration.
- **`predictive_modelling.py`** – Python script for churn prediction using logistic regression/classification models.
- **`model_outputs/`** – Images and charts generated from predictive modelling.
- **`telco_dashboard.pdf`** – Tableau dashboard summarizing churn insights and model results.

---

## Tools & Technologies
- **Python**: pandas, scikit-learn, matplotlib, seaborn, sqlite3
- **SQL**: Data extraction and transformation (via SQLite in Python)
- **Tableau**: Dashboard creation and visualization
- **Database**: SQLite

---

## Key Insights
- Identified customer segments with high churn risk based on contract type, payment method, and tenure.
- Built a churn prediction model with [insert accuracy %, e.g. **85% accuracy**] to assist retention strategies.
- Created an interactive Tableau dashboard for quick, data-driven decision-making.


---

## How to Use
1. Open `telco.db` or `telco_clean.csv` for the dataset.
2. Run `sql_queries.py` to perform SQL-based data exploration.
3. Run `predictive_modelling.py` to train and evaluate churn prediction models.
4. View `telco_dashboard.pdf` or the Tableau Public link for interactive analysis.

---

## Project Workflow
1. **Data Cleaning & Preparation** – Removed missing values, standardized formats.
2. **Data Exploration (SQL)** – Queried database for key metrics.
3. **Predictive Modelling (Python)** – Logistic regression and classification models.
4. **Visualization (Tableau)** – Created dashboard for churn insights.
