# AB Test Conversion Significance

# A/B Test Results Evaluation: Subscription Pricing Analysis 📊

## 📋 Project Overview
This project focuses on evaluating the results of an A/B test conducted for a mobile application. The primary business goal was to optimize subscription revenue by testing two different pricing framings. The analysis determines whether the variation in conversion rates is statistically significant and provides data-driven recommendations for stakeholders.

### 🧪 Test Setup
* **Variant A (Control Group):** Users were offered a premium subscription for **$4.99**.
* **Variant B (Test Group):** Users were offered the same subscription but framed as a **50% discount promotional offer**.
* **Primary Metric:** Install-to-payment conversion rate (assuming additional product metrics remained stable).

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python 
* **Data Manipulation:** Pandas, NumPy
* **Statistical Analysis:** SciPy (stats), Statsmodels
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

---

## 🚀 Key Steps & Analysis Workflow

1. **Exploratory Data Analysis (EDA):**
   * Loaded raw experimental data (`ab_test_data.csv`).
   * Calculated sample sizes (total users) and absolute conversion counts for both groups.
   * Computed baseline conversion rates.
   * Determined the test duration (start date, end date, and total days).

2. **Statistical Hypothesis Testing:**
   * Defined Null ($H_0$) and Alternative ($H_1$) hypotheses.
   * Selected and applied the appropriate statistical criterion (**Z-test for proportions** / **Chi-Square test**).
   * Calculated the test statistic and **p-value** to determine statistical significance at $\alpha = 0.05$.

3. **Data Visualization:**
   * Built visual representations to compare mean conversion rates between Group A and Group B.
   * Included **95% Confidence Intervals (CI)** to demonstrate the stability and variance of the metric.

---

## 📈 Visualizations & Insights
*The repository includes a Jupyter Notebook with complete step-by-step code and generated plots.*

* **Statistical Summary:** Detailed calculation of whether we have enough statistical evidence to reject the Null Hypothesis.
* **Business Deliverable:** A comprehensive executive presentation summarizing the findings.

💻 **[View Python Analysis & Code Notebook](https://github.com/podolskayaia2012-dot/ab-test-conversion-significance/blob/main/Analysis%20and%20presentation%20of%20test%20results%20-%20Python%20code.ipynb)**
📦 **[Download Full PDF Presentation with Insights & Recommendations](https://github.com/podolskayaia2012-dot/ab-test-conversion-significance/blob/main/Analysis%20and%20presentation%20of%20test%20results.pdf)**
---

## 🎯 Final Conclusions & Functional Contribution
* Formulated clean, production-ready Python code for automating A/B test evaluation.
* Handled full data preprocessing, anomaly checking, and statistical calculation pipeline.
* Translated raw p-values and confidence intervals into clear business language, helping the team decide whether to roll out the promotional framing globally.


