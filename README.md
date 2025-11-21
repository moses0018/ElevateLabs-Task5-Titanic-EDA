# Titanic Exploratory Data Analysis (EDA)

## Task 5 – Elevate Labs Internship Program

This project focuses on performing Exploratory Data Analysis (EDA) on the Titanic dataset to identify patterns, trends, and survival relationships using Python.

---

## 🎯 Objective
- Understand the structure of the Titanic dataset  
- Analyze patterns related to survival  
- Explore numerical & categorical features  
- Build visualizations for statistical insights  
- Document findings into a PDF + Notebook

---

## 🛠️ Tools & Technologies
- Python  
- Jupyter Notebook  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## 📂 Dataset
**Source:** Titanic Dataset from Kaggle  
File used: `train.csv`

Dataset contains:
- 891 rows  
- 12 columns  
- Numerical, categorical, and text variables  

---

## 📊 Steps Performed

### 1. Data Understanding
- Loaded dataset  
- Checked `.info()`, `.describe()`, `.shape()`  
- Identified missing values  
- Inspected data types  

### 2. Data Cleaning
- Treated missing values (Age, Embarked, Cabin)  
- Standardized column names  
- Converted numerical columns where needed  

### 3. Univariate Analysis
Visualizations created:
- Age histogram  
- Fare histogram + boxplot  
- Survived countplot  
- Pclass, Embarked, Sex distribution  

### 4. Bivariate Analysis
Explored relationships:
- Sex vs Survived  
- Pclass vs Survived  
- Embarked vs Survived  
- Age vs Survived  
- Fare vs Survived  

### 5. Correlation Analysis
- Generated correlation heatmap using numeric-only features  
- Observed relationships among Fare, Pclass, Survived  

### 6. Pairplot
Compared:
- Survived  
- Age  
- Fare  

### 7. Insights
Added observations for each graph + overall summary.

---

## 🧠 Key Insights

### Survival Patterns
- Females had a significantly higher survival rate  
- First-class passengers survived more often  
- Higher fare passengers had better survival odds  

### Demographics
- Majority passengers were men  
- Most traveled in 3rd class  
- Age peaks around 20–40 years  

### Correlations
- Fare ↗ increases chance of survival  
- Pclass ↘ lowers survival probability  
- SibSp & Parch correlations are weak  

### Missing Data
- Cabin column mostly unusable  
- Age requires imputation  
- Embarked has minor missing values  

---

## 📁 Deliverables
- `Titanic_EDA.ipynb` (Jupyter Notebook)  
- `Titanic_EDA.pdf` (PDF Report)  
- `README.md`  

---

## ▶️ How to Run
```bash
pip install pandas numpy seaborn matplotlib
jupyter notebook
