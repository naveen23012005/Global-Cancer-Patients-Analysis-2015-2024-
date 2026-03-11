# 🧬 Global Cancer Patients Analysis (2015–2024)

## 📌 Project Overview

This project analyzes a **global cancer patient dataset (2015–2024)** to explore factors affecting **cancer severity, treatment cost, and patient survival**. The analysis uses **exploratory data analysis, statistical testing, and visualization** to identify patterns related to lifestyle factors, genetic risk, environmental exposure, and demographic characteristics.

The goal is to generate **data-driven insights** that help understand the **economic burden of cancer treatment and factors influencing cancer severity**.

---

# 🎯 Project Objectives

The main objectives of this project are:

* Identify the **most important factors influencing cancer severity**
* Explore the **economic burden of cancer treatment across countries and demographics**
* Examine whether **higher treatment costs lead to longer survival years**
* Evaluate whether **higher cancer stages lead to greater treatment costs and reduced survival**
* Investigate whether **genetic risk amplifies the negative effects of smoking on cancer severity**

---

# 📂 Dataset Description

The dataset contains **50,000 cancer patient records** collected from **2015–2024** across multiple countries.

### Key Variables

| Column                | Description                          |
| --------------------- | ------------------------------------ |
| Age                   | Age of the patient                   |
| Gender                | Gender of the patient                |
| Country_Region        | Country where the patient is located |
| Cancer_Type           | Type of cancer                       |
| Cancer_Stage          | Stage of cancer (Stage 0 – Stage IV) |
| Smoking               | Smoking exposure level               |
| Alcohol_Use           | Alcohol consumption level            |
| Air_Pollution         | Environmental pollution exposure     |
| Obesity_Level         | Obesity risk level                   |
| Genetic_Risk          | Genetic predisposition risk          |
| Treatment_Cost_USD    | Cost of cancer treatment             |
| Survival_Years        | Number of years the patient survived |
| Target_Severity_Score | Overall cancer severity score        |

---

# 🔍 Analysis Performed

## 1️⃣ Exploratory Data Analysis (EDA)

* Data cleaning and preprocessing
* Age group categorization
* Country-wise treatment cost comparison
* Demographic analysis

---

## 2️⃣ Feature Importance Analysis

Machine learning techniques were used to determine which factors most strongly influence **cancer severity**.

### Key Finding

* **Smoking and Genetic Risk are the most important predictors of cancer severity.**

---

## 3️⃣ Economic Burden Analysis

Treatment costs were analyzed across:

* Different **countries**
* **Age groups**
* **Gender categories**

### Key Insight

Cancer treatment costs remain **consistently high globally**, averaging around **$50,000–$54,000 USD**.

---

## 4️⃣ Treatment Cost vs Survival Analysis

Correlation analysis was performed using:

* **Pearson correlation**
* **Spearman correlation**

### Result

There is **no statistically significant relationship** between treatment cost and survival years.

This suggests that **higher treatment cost does not necessarily lead to longer survival**.

---

## 5️⃣ Cancer Stage Impact Analysis

A **One-Way ANOVA test** was performed to evaluate whether cancer stage affects:

* Treatment cost
* Cancer severity

### Result

The analysis showed **no statistically significant difference** in treatment cost or severity across cancer stages.

---

## 6️⃣ Smoking and Genetic Risk Interaction

A **Two-Way ANOVA test** was conducted to examine whether **genetic risk amplifies the impact of smoking on cancer severity**.

### Results

* Smoking significantly increases cancer severity.
* Genetic risk significantly increases cancer severity.
* However, the **interaction between smoking and genetic risk was not statistically significant**.

This means **genetic risk does not significantly amplify the effect of smoking** in this dataset.

---

# 📊 Visualizations

The project includes several visualizations such as:

* Feature Importance Bar Chart
* Scatter Plot (Treatment Cost vs Survival Years)
* Country-wise Treatment Cost Comparison
* Age Group Cost Analysis
* Interaction Analysis Plots

---

# 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Statsmodels
* Jupyter Notebook

---

# 📁 Project Structure

```
global-cancer-analysis/
│
├── data/
│   └── global_cancer_patients.csv
│
├── notebooks/
│   └── global_cancer_patients.ipynb
│
├── visualizations/
│   └── plots and charts
│
└── README.md
```

---

# 🚀 Future Improvements

Possible future enhancements include:

* Building **predictive machine learning models** for cancer severity
* Performing **survival analysis using Kaplan–Meier curves**
* Applying **advanced statistical modeling**
* Expanding the dataset with more **real-world clinical data**

---

# 👨‍💻 Author

**Challa Naveen**

Data Analytics / Data Science Project

---

