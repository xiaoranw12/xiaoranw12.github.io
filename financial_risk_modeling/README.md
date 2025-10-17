# Financial Risk Modeling

## 🔹 Project Overview
This project focuses on predicting credit risk for corporate and individual clients using large-scale financial datasets.  
The goal was to quantify the likelihood of default and identify key risk factors to support data-driven lending and investment decisions.

## 🔹 Data / Sources
- **Source:** ASML internal credit dataset (anonymized)  
- **Size:** ~50,000 records, 20+ features  
- **Key Variables:** Credit score, loan amount, repayment history, outstanding balance, default status  

## 🔹 Methods & Tools
- **Programming:** Python (Pandas, NumPy, Scikit-learn), SQL  
- **Models:** Logistic Regression, Random Forest  
- **Evaluation Metrics:** ROC-AUC, F1-score, confusion matrix  
- **Visualization:** Matplotlib, Seaborn, Power BI

## 🔹 Results / Highlights
- Random Forest model achieved **ROC-AUC = 0.85** and **F1-score = 0.78**  
- Key predictors of credit default included repayment history, credit utilization ratio, and outstanding balances  
- Visualized risk distribution across different customer segments for strategic decision-making  

![Credit Risk Distribution](../images/financial_risk_modeling.png)

## 🔹 How to Run
1. Clone the repository: `git clone https://github.com/xiaoranw12/Portfolio.git`  
2. Navigate to the project folder: `cd Portfolio/financial_risk_modeling`  
3. Install dependencies: `pip install -r requirements.txt`  
4. Run `main.py` to reproduce the analysis results

## 🔹 Next Steps / Future Work
- Deploy an interactive dashboard for real-time credit risk monitoring  
- Test and validate models on additional datasets for improved robustness  
- Explore advanced modeling techniques such as XGBoost or Gradient Boosting  
- Integrate macroeconomic indicators to enhance predictive accuracy
