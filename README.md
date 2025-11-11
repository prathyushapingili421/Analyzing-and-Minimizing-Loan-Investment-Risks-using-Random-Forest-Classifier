# 💳 Loan Default Risk Prediction – Random Forest Classifier & Power BI Dashboard

**Machine Learning ▪ Predictive Modeling ▪ Data Visualization**  
*Python • Pandas • Random Forest • Seaborn • Power BI*

---

## 📌 Project Overview

The goal of this project is to **predict loan default risk** using real LendingClub loan data and live survey responses collected from students.  
This enables financial institutions to identify **high-risk borrowers** before issuing a loan and make data-driven lending decisions.

---

## 🛠 Tech Stack

| Component | Technology Used |
|----------|-----------------|
| **Dataset** | LendingClub Loan Dataset (Kaggle) + 100+ student survey responses |
| **Languages** | Python (Pandas, NumPy, Matplotlib, Seaborn) |
| **Modeling** | Random Forest Classifier |
| **Visualization** | Power BI |
| **Collaboration & Processing** | Jupyter Notebook, Excel |

---

## 📂 Dataset Details

The project uses **two datasets**:

1. **LendingClub Loan Records (Kaggle)** – contains loan amount, income, payment status, debt-to-income ratio, etc.
2. **Live Survey Dataset** – responses from 100+ students on loan type and interest rates.

| Data Type | Key Attributes |
|-----------|----------------|
| Loan Dataset | Loan amount, repayment term, annual income, verification status, loan purpose, loan status |
| Survey Responses | Interest rate, income type, loan source preference |

---

## 🧠 Approach

### 🔹 1. Data Cleaning & Preprocessing
✔ Cleaned and prepared LendingClub loan data along with **100+ survey responses**  
✔ Handled missing values, normalized formats, and performed **feature engineering**  
✔ Converted categorical values to numeric using label encoding

### 🔹 2. Exploratory Data Analysis (EDA)
Analyzed patterns such as:

- Loan amount vs. default behavior  
- Term (36 vs 60 months) preferences  
- Income type vs. repayment capability  
- Debt-to-income ratio impact on default likelihood  

### 🔹 3. Modeling
Built a **Random Forest Classifier** to predict default risk.

➡️ **~80% accuracy on unseen test data**

Identified top predictors:

- Loan amount  
- Verification status  
- Loan purpose  
- Annual income  

### 🔹 4. Dashboard Visualization (Power BI)
Designed an interactive **Power BI dashboard** to visualize:

- Loan interest trends
- Loan repayment vs. charged-off distribution
- Borrower segmentation based on income/loan amount
- Loan purpose and risk comparison

---

## 📊 Key Insights

| Finding | Impact |
|--------|-------|
| 36-month loans had better repayment rates | Shorter terms reduce risk |
| Higher loan amount = higher default probability | Helps adjust lending limits |
| Income verification strongly correlates with repayment | Improves risk assessment |
| Certain loan purposes (credit card, debt consolidation) have higher default rates | Enables targeted eligibility criteria |

---

## 🚀 Results

- Random Forest achieved **~80% test accuracy**
- Dashboard enables lenders to **identify high-risk loan applications**
- Predictive insight reduces exposure to potential bad debt

---

## ✅ Business Impact
✔ Helps lenders assess borrower risk before approval.

✔ Reduces likelihood of default and financial loss.

✔ Enables data-driven loan decisions supported by visual analytics.

## 📜 License
⚠️ For academic and learning use only.

