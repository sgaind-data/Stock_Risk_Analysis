# 📈 Stock Investment Risk Analysis

**Author:** Sarika Gaind  

## 📌 Project Overview
This project performs risk analysis of financial stocks by evaluating their volatility and classifying them as **low-risk** or **high-risk**. Using regression models and the Beta coefficient, we determine the risk profile of selected stocks relative to the S&P 500 benchmark.  

## 🔍 Methods
- Data collection: Tesla, Apple, Microsoft, and Walmart stock returns (Yahoo Finance)  
- Regression Models:
  - Linear Regression
  - Polynomial Regression  
- Risk Classification: Beta > 1.0 = High Risk, Beta < 1.0 = Low Risk  

## 📊 Key Insights
- Apple, Tesla, and Microsoft → **high-risk** relative to market  
- Walmart → **low-risk** relative to market  
- Polynomial regression fit slightly better than linear regression (higher R² values).  

## 🛠️ Tools & Libraries
- Python (Quantstats, NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn)  

## 📂 Repository Contents
- `code/` → Python scripts & Jupyter notebooks  
- `report/` → Project report (PDF)  

## 📜 Note
This project was completed as part of an academic course and is shared for educational and demonstration purposes only.
