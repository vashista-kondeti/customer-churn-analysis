# customer-churn-analysis
A data analysis project to identify factors contributing to customer churn for a subscription based business using Python, SQL, and Tableau

## 📌 Objective

The purpose of this project is to analyze customer churn behavior for a subscription-based business.Using Python, SQL, and Tableau, I aim to uncover the key factors driving customer attrition and help businesses reduce churn through actionable insights.

**Goals:**
- Identify patterns and trends in customer churn
- Segment at-risk customers using data-driven insights
- Visualize churn drivers for stakeholders using Tableau dashboards



---

## 🛠️ Tools & Technologies

- **Python** (Pandas, Matplotlib, Seaborn, Scikit-learn)
- **SQL** (SQLite/PostgreSQL for segmentation queries)
- **Tableau** (Interactive dashboards for data storytelling)
- **Jupyter Notebook / VS Code**
- **GitHub** (for version control and documentation)

---

## 🧩 Dataset

- **Name:** Telco Customer Churn  
- **Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Records:** 7,043 customer rows  
- **Features:** Demographics, service usage, billing information, churn status

---

## 🔍 Project Phases

### ✅ Phase 1: Planning & Data Collection
- Defined the business objective and success metrics.
- Downloaded the Telco Churn dataset from Kaggle.
- Loaded and explored the dataset using Pandas.

### ✅ Phase 2: Data Cleaning & Preprocessing
- Converted `TotalCharges` column to numeric (handled blanks).
- Dealt with missing values and encoded categorical variables.
- Performed sanity checks and removed duplicates.

### ✅ Phase 3: SQL-Based Customer Segmentation
- Created a relational database using SQLite.
- Wrote SQL queries to extract subsets like:
  - Customers with monthly contracts
  - Senior citizens with high churn rates
  - Customers with fiber optic internet and high charges

### ✅ Phase 4: Exploratory Data Analysis (EDA) with Python
- Visualized churn by tenure, contract type, and internet service.
- Plotted heatmaps to identify feature correlations.
- Observed that longer-term contracts significantly reduce churn.

### ✅ Phase 5: Predictive Modeling (Optional)
- Built a logistic regression model to predict churn probability.
- Evaluated with accuracy, precision, and confusion matrix.

### ✅ Phase 6: Tableau Dashboard
- Created an interactive dashboard showing:
  - Overall churn rate
  - Churn by contract type and payment method
  - Churn by tenure and internet service
- **View it here:** [Tableau Public Dashboard](#) *(Insert your actual link)*

### ✅ Phase 7: Documentation & Sharing
- Wrote this detailed README.
- Shared the project on LinkedIn to demonstrate data storytelling skills.

---

## 📈 Key Insights

- **Contract type** is a major churn driver: customers on month-to-month plans are far more likely to leave.
- **Senior citizens** show a slightly higher churn rate.
- **Fiber optic internet users** churn more than DSL users — possibly due to pricing or service issues.
- Customers paying via **electronic check** churn the most, suggesting this group may be less engaged.

---

## 📌 Files in This Repo

| File/Folder | Description |
|-------------|-------------|
| `load_data.py` | Loads and inspects the dataset |
| `cleaning.py` | Cleans and preprocesses the data |
| `sql_queries.sql` | SQL queries for segmentation |
| `eda_visuals.ipynb` | Notebook with visualizations |
| `churn_model.py` | (Optional) Predictive model |
| `README.md` | Project documentation |

---

## 🤝 Let’s Connect

If you found this project insightful or have feedback, feel free to connect with me on [LinkedIn](#) or check out more of my work on [GitHub](#).

---

