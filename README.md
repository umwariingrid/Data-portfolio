# Data Analysis Portfolio.

1. About Me
   I am an aspiring data analyst passionate about transforming raw data into actionable insights.
   This repository showcases two complete data analysis projects using Python, SQL, and data visualization tools.

2. Skills
   - Data Analysis: Python (Pandas, NumPy), SQL, Excel
   - Visualization: Power BI, Matplotlib, Seaborn
   - Reporting: Automated Reports, Executive Dashboards.

3. Project 1: Financial Fraud Detection Analysis
- Overview
  Detected Fraudulent transcations using synthetic data generated with Python's Faker
  library. Analyzed patterns to identify fraud indicators including unusual transcation
  amounts, timing anomalies, and behavorial patterns.
   - Tools used
     Python (Pandas, NumPy, Matplotlib, Seaborn)
     Faker library for synthetic data
     Jupyter Notebooks for analysis
- Key Dimensions Analyzed:
  Transaction type and amount
  Time of transcation
  customer behavior patterns
- Key Findings
  Transfer: 8.2% fraud rate
  Withdrawal: 6.5% fraud rate
  Purchase: 3.1% fraud rate
  Deposit: 2.8% fraud rate
  "Transfers and withdrawals carry significantly higher fraud risk than purchases or deposits.

How to Run This Project
1. Clone the repo
   git clone
2. Navigate to project folder
   cd fraud-analysis
3. Install dependencies
   pip install -r requirements.txt
4. Generate synthetic dataset
   python generate_fraud_data.py
5. Run the analysis
   python fraud_analysis.py
     
