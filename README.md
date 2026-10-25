# AI-Based Credit Risk Analysis

## Project Overview
This project analyzes credit risk in banking using data analysis and machine learning techniques. It explores customer information and historical credit-risk labels to understand patterns associated with good-risk and bad-risk customers.

The project is developed as part of the **AI for Business** academic mini-project.

## Business Problem
Banks need to assess credit risk before approving loans. Manual assessment can take time and may not consistently identify patterns in customer data. This project explores how machine learning can support credit-risk analysis and help analysts make more informed decisions.

## Objectives
- Analyze customer and credit-related data.
- Clean missing values and prepare the dataset.
- Build a Logistic Regression classification model.
- Explore customer segments using K-Means clustering.
- Evaluate model performance using classification metrics.
- Discuss AI governance, fairness, explainability, and limitations.

## Tools and Technologies
- Python
- Pandas and NumPy
- Scikit-learn
- Jupyter Notebook / Google Colab
- Microsoft Excel
- Power BI (for dashboard development)

## Machine Learning Methods
**1. Logistic Regression:** Used to classify records into the dataset's historical `good` and `bad` risk categories.

**2. K-Means Clustering:** Used to explore customer segments based on selected numerical features.

## Dataset
The project uses the German Credit dataset (`german_credit_data.csv`).

The dataset includes fields such as age, job, housing, savings account, checking account, credit amount, loan duration, purpose, and historical risk category.

**Note:** Verify the dataset's original source and licence before redistributing it. If redistribution is not permitted, provide source and download instructions instead of uploading the dataset.

## Important Limitations
- The historical risk labels do not necessarily represent confirmed future loan defaults.
- The dataset comes from a German context and may not generalize to current Indian banking customers.
- The model's performance is not sufficient to justify automated lending decisions.
- Predictions should be reviewed by qualified human decision-makers.

## Repository Structure
```text
AI-Based-Credit-Risk-Analysis/
├── README.md
├── notebooks/
│   └── credit_risk_model.ipynb
├── data/
│   └── README.md
├── dashboard/
│   └── dashboard_screenshots/
└── report/
    └── project_report.pdf
```

*Add the folders and files as you create them.*

## Expected Learning Outcomes
- Understanding business problems through data analysis.
- Applying basic machine learning techniques.
- Interpreting model evaluation metrics.
- Understanding responsible AI and credit-risk governance.

## Disclaimer
This project is for academic and educational purposes only. It is not a production-ready credit-scoring system and should not be used to approve or reject real loan applications.
# AI-Based-Credit-Risk-Analysis
AI-Based Credit Risk Analysis using Machine Learning, Logistic Regression, K-Means Clustering, and Data Visualization.
