# 🚢 Growth Insight Report – Titanic Passenger Analysis

## 📊 Project Overview

This project analyzes the Titanic dataset to uncover key factors influencing passenger survival. The goal is to simulate a real-world business scenario where a cruise company uses data to improve safety, customer segmentation, and premium service strategy.

The analysis follows an end-to-end workflow including data cleaning, exploratory data analysis (EDA), visualization (Power BI), and hypothesis testing.

---

## 🎯 Business Objective

To identify:

* Key passenger segments with higher survival rates
* Impact of ticket class and fare on survival
* Whether gender significantly influenced survival outcomes

---

## 🛠️ Tools & Technologies

* Python (Pandas, NumPy, SciPy)
* Power BI (Dashboard & Visualizations)
* Jupyter Notebook
* Statistical Testing (T-test)

---

## 📂 Dataset Features

* Passenger demographics (Age, Gender)
* Travel class (Pclass)
* Ticket fare
* Family information (SibSp, Parch)
* Survival status (0 = No, 1 = Yes)

---

## 🔍 Key Insights

### 1. Gender Strongly Influenced Survival

* Female passengers had significantly higher survival rates compared to males
* Hypothesis testing confirmed this difference is statistically significant (p < 0.05)

👉 Interpretation: Emergency protocols prioritized women and children

---

### 2. Higher-Class Passengers Had Better Survival

* First-class passengers had the highest survival rates
* Third-class passengers had the lowest survival rates

👉 Interpretation: Access to resources and evacuation priority played a major role

---

### 3. Fare Correlates with Survival

* Passengers who paid higher fares had better survival outcomes

👉 Interpretation: Higher-paying customers received better safety access

---

### 4. Age-Based Trends

* Children had relatively higher survival rates
* Adults and seniors showed lower survival probability

👉 Interpretation: Rescue efforts favored vulnerable groups

---

### 5. Clear Inequality in Survival Outcomes

* Survival was not random
* It was influenced by gender, class, and economic status

---

## 📈 Hypothesis Testing

**Test Conducted:** Independent T-test (Male vs Female Survival)

* Null Hypothesis (H0): No difference in survival rates
* Alternative Hypothesis (H1): Significant difference exists

**Result:**

* P-value ≈ 0 (1.4e-69)
* Conclusion: Reject H0

👉 There is a statistically significant difference in survival rates between genders

---

## 📊 Dashboard (Power BI)

The dashboard includes:

* Survival Rate by Gender
* Survival Rate by Class
* Survival by Age Group
* Fare Distribution
* KPI Cards (Total Passengers, Avg Fare, Survival Rate)

---

## 💡 Executive Recommendations

### 1. Ensure Equal Safety Access

Standardize emergency procedures across all passenger classes to avoid inequality in survival outcomes.

---

### 2. Improve Safety Infrastructure for Economy Class

Enhance evacuation access, safety drills, and resource availability for lower-class passengers.

---

### 3. Data-Driven Customer Segmentation

Use demographic and behavioral data to design targeted safety and service strategies.

---

### 4. Prioritize Vulnerable Groups Strategically

Maintain priority for children and high-risk individuals, but ensure fairness across all segments.

---

### 5. Strengthen Premium Service Strategy

High-value customers expect better service — use this insight to design premium offerings while maintaining fairness.

---

## 📌 Conclusion

The analysis reveals that survival outcomes were heavily influenced by gender, class, and fare. These findings highlight the importance of equitable safety measures and data-driven decision-making in improving customer outcomes and operational efficiency.

---

## 📁 Project Structure

```
project/
│
├── data/
│   ├── raw/
│   └── cleaned/
│
├── notebook/
│   └── analysis.ipynb
│
├── visuals/
│   └── dashboard.pbix
│
├── report/
│   ├── slides.pdf
│   └── executive_summary.pdf
```

---

## 🚀 Real-World Application

This project demonstrates how data analysis can drive:

* Business decision-making
* Customer segmentation
* Risk management
* Strategic planning

---


