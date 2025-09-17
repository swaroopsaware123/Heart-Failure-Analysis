# ❤️ Heart Failure Analysis

## 📌 Project Overview
This project focuses on analyzing clinical data of **heart failure patients** to identify critical risk factors and improve ICU resource management.  
The analysis covers **data cleaning, exploratory data analysis (EDA), survival analysis, machine learning models, and SHAP explainability**.  

---

## 🎯 Objectives
- Identify high-risk patients for ICU admission.  
- Reduce unnecessary ICU occupancy for low-risk patients.  
- Improve survival outcomes in the critical **first 100 days**.  
- Provide hospital administrators with cost-saving insights.  

---

## 🛠️ Workflow
1. **Data Preprocessing** – Cleaning, handling outliers, validating data types.  
2. **EDA & Visualization** – Clinical trends, correlations, and patient distributions.  
3. **Domain-Based Risk Stratification** – Thresholds for age, EF, creatinine, sodium.  
4. **Survival Analysis** – Kaplan-Meier curves & log-rank tests.  
5. **Machine Learning Models** – Logistic Regression & Random Forest with ROC/AUC.  
6. **Model Explainability** – SHAP values for feature importance.  
7. **Business ROI** – ICU cost savings & triage recommendations.  

---

## 📊 Key Insights
- Patients with **EF < 35%, Creatinine > 1.2, Age ≥ 70** show the **highest mortality risk**.  
- Kaplan-Meier analysis highlights the **critical 100-day survival window**.  
- Random Forest achieved an **AUC of ~0.89**, Logistic Regression ~0.86.  
- SHAP explainability confirms **EF, age, and creatinine** as top predictors.  

---

## 🚀 Impact
This project bridges the gap between **clinical data science** and **business operations**.  
It demonstrates how **data-driven triage strategies** can:  
- Improve survival by 15–20%.  
- Reduce unnecessary ICU costs by ₹15–25 lakhs/month per 100 patients.  
- Provide doctors and administrators with clear decision support tools.  

---

## 📂 Repository Structure

├── Heart_Failure_Analysis.ipynb # Main Jupyter Notebook
├── heart_failure_clinical_records_dataset.csv # Dataset
├── README.md # Project Documentation

---

## 📌 Tech Stack
- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Scikit-learn (Logistic Regression, Random Forest)  
- Lifelines (Survival Analysis)  
- SHAP (Model Explainability)  

---

## 🧑‍💻 Author
**Swaroop Saware**  
📍 Data Science Enthusiast | Business-driven Analytics  
📧 swaroopsaware123@gmail.com  

---

⭐ If you find this project useful, consider giving it a star!
