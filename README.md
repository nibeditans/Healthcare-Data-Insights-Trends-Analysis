# 🏥 Healthcare Data Insights & Trends Analysis

This project performs exploratory data analysis (EDA) on a synthetic healthcare dataset using Python. Although the dataset lacks meaningful real-world insights due to its balanced and likely synthetic nature, the project highlights core data analysis workflows, including preprocessing, feature engineering, visualization, and an experimental machine learning attempt.

---

## 📁 Dataset Overview

- **File Name**: `healthcare_dataset.csv`  
- **Shape**: (55,500 rows × 15 columns)  
- **Missing Values**: None  
- **Data Type**: Synthetic, clean, well-structured

### Key Columns
- `Name`, `Age`, `Gender`, `Blood Type`
- `Medical Condition`, `Date of Admission`, `Discharge Date`
- `Doctor`, `Hospital`, `Insurance Provider`, `Billing Amount`
- `Room Number`, `Admission Type`, `Medication`, `Test Results`

---

## 🧪 Tools & Technologies Used

- **Python**  
- **NumPy**, **Pandas** – Data manipulation and preprocessing  
- **Matplotlib**, **Seaborn** – Data visualization  
- **Scikit-learn** – Basic machine learning models  
- **Jupyter Notebook** – Analysis and documentation  

---

## 🔍 Project Phases

### 1. Data Cleaning & Preprocessing
- Verified datatypes, parsed datetime columns
- Created new features: `Admission Year`, `Admission Month`, `Length of Stay`

### 2. Exploratory Data Analysis (EDA)
- Univariate and bivariate visualizations
- Analyzed distributions (age, billing amount, gender, etc.)
- Identified synthetic patterns in features (e.g., flat gender/blood type distribution, uniform length of stay)
- Found no real-world trends or correlations

### 3. High-Cardinality Features
- Evaluated distributions for `Doctor`, `Hospital`, `Insurance Provider`, etc.
- Only `Top 5 Doctors` and `Top 5 Hospitals` provided marginal insight

### 4. Temporal Analysis
- Admissions distributed almost equally across months and years
- No seasonal patterns, further confirming synthetic nature

### 5. Experimental ML Task
- Performed one classification task using `Medical Condition` as target
- Basic preprocessing using `LabelEncoder`
- Trained a `RandomForestClassifier` model
- **Accuracy ~ 28.7%**, confirming no meaningful predictive relationships

---

## 📌 Conclusion

> While the dataset lacked real-world insights from a data analysis perspective, its synthetic structure made it ideal for practicing core DA workflows and ML experimentation. The project showcased EDA, feature engineering, and a full end-to-end analysis pipeline.

---
