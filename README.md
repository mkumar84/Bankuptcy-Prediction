# 📉 Bankruptcy Prediction
# Machine‑learning model to identify early signs of financial distress for lenders and risk teams

## 🧩 Overview
Financial institutions need early warning indicators to identify companies at risk of bankruptcy. Traditional risk assessments rely heavily on manual reviews, lagging indicators, and inconsistent scoring frameworks. This leads to delayed interventions and increased credit losses.
The **Bankruptcy Prediction Model** uses machine‑learning techniques to predict financial distress based on historical financial ratios and behavioral indicators. It supports risk teams in prioritizing reviews, improving portfolio monitoring, and making proactive decisions.

## 🎯 Problem
Risk teams face several challenges:
- Lagging indicators make it difficult to detect distress early
- Manual reviews are slow and inconsistent
- Large portfolios make it hard to prioritize high‑risk entities
- Traditional scoring models lack adaptability

## 🚀 Goal
Build a predictive model that:
- Identifies high‑risk companies early
- Improves prioritization for risk analysts
- Supports proactive interventions
- Enhances portfolio‑level monitoring

## 👤 My Role
- Defined the problem and success metrics with risk stakeholders
- Selected features based on financial theory and domain knowledge
- Evaluated model performance and trade‑offs (precision vs. recall)
- Positioned the model as a decision‑support tool, not a black box
- Created a roadmap for operationalization

## 🛠 Approach
1. Data Preparation
- Cleaned and standardized financial statements
- Engineered features such as liquidity ratios, leverage ratios, profitability metrics, and cash‑flow indicators
- Balanced the dataset to address class imbalance
2. Model Development
- Tested multiple algorithms (Logistic Regression, Random Forest, XGBoost)
- Tuned hyperparameters for optimal performance
- Selected the model with the best balance of recall and precision
3. Evaluation
- Confusion matrix to understand false positives/negatives
- ROC‑AUC for overall discriminatory power
- Precision‑Recall trade‑off analysis for risk appetite alignment

## 🧠 Architecture
Raw Financial Data → Feature Engineering → ML Model → Risk Score → Analyst Review

## 📊 Example Output
**Input:**
Financial ratios for a company over the last 3 years
**Output:**
- Bankruptcy risk score: 0.82
- Key drivers: high leverage, declining liquidity, negative cash flow
- Recommendation: prioritize for manual review

## 🏁 Outcome
- Improved early detection of distressed companies
- Better prioritization for risk analysts
- More consistent and data‑driven risk assessments
- Foundation for portfolio‑level risk dashboards

## 🔮 Roadmap
- Add explainability (SHAP values)
- Add time‑series modeling
- Integrate macroeconomic indicators
- Build a risk‑tiering dashboard
- Add scenario analysis

## 📁 Repository Structure
/data               → Sample datasets  
/notebooks          → Model development notebooks  
/models             → Trained models  
README.md           → Documentation


If you want, I can now polish all four READMEs into a consistent visual style, or help you integrate them into your Vercel portfolio so each project appears as a clean case study.
