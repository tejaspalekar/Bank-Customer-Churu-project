# Bank Customer Churn Analytics Project

A data analytics project focused on understanding customer churn in a bank using Python, Pandas, NumPy, Matplotlib, Seaborn, Excel, and Power BI. The project analyzes customer behavior patterns to identify which factors are associated with churn and how they vary by geography, age, activity, and account profile.

## Project Overview

This project explores a synthetic bank customer dataset containing customer demographics, account details, product usage, activity status, and churn flag. The goal is to discover patterns behind customer attrition and convert those insights into business-friendly analysis.

## Objectives

- Analyze customer churn trends across different segments
- Identify key drivers of churn
- Understand how geography, age, tenure, balance, and product usage influence churn
- Clean and prepare raw data for analysis
- Create a dashboard-ready dataset and insights

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Microsoft Excel
- Power BI

## Dataset

The repository includes the following files:

- `Bank_Churn.csv` – main bank customer churn dataset
- `Bank_Churn_Data_Dictionary.csv` – description of each column/field
- `Bank_Churn_Messy.xlsx` – raw messy Excel file used for data preparation
- `Bank project.ipynb` – notebook containing the analysis workflow

### Key Features in the Dataset

The dataset includes customer-level attributes such as:

- Customer ID
- Surname
- Credit score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of products
- Credit card ownership
- Activity status
- Estimated salary
- Churn flag (`Exited`)

## Project Workflow

1. Load and inspect the raw dataset
2. Clean and preprocess data
3. Handle missing or messy values
4. Explore churn patterns using EDA
5. Visualize churn behavior by key customer attributes
6. Interpret key churn drivers
7. Prepare findings for reporting and dashboarding

## Repository Structure

```text
Bank-Customer-Churu-project/
├── Bank project.ipynb
├── Bank_Churn.csv
├── Bank_Churn_Data_Dictionary.csv
├── Bank_Churn_Messy.xlsx
├── README.md
└── .gitignore
```

## How to Run

1. Clone the repository
2. Open the notebook: `Bank project.ipynb`
3. Install the required Python libraries if needed:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

4. Run the notebook to reproduce the analysis

## Business Use Case

This project is useful for banking and customer analytics teams who want to:

- reduce customer churn
- improve retention strategies
- understand high-risk customer segments
- support data-driven decision making

## Notes

The project is designed as a practical churn analytics case study and can be extended with:

- predictive modeling
- machine learning classification
- retention strategy recommendations
- interactive Power BI dashboards

## License

This project is for educational and portfolio purposes.
