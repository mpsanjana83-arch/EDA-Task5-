# EDA-Task5-
 Exploratory Data Analysis (EDA) 

# **Titanic Exploratory Data Analysis (EDA)**

## **Project Overview**

This project performs an **Exploratory Data Analysis (EDA)** on the Titanic dataset to extract insights, identify trends, and understand relationships between variables affecting passenger survival.

---

## **Objective**

* Explore the dataset to identify patterns, anomalies, and relationships.
* Visualize key features to understand factors influencing survival.
* Summarize findings to provide actionable insights.

---

## **Dataset**

* **Name:** Titanic Dataset
* **Source:** Public dataset (commonly used for EDA and ML practice)
* **Features:** PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked
* **Rows:** 891
* **Columns:** 12

---

## **Tools & Libraries**

* Python 3
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## **Steps Performed**

1. **Data Loading & Inspection:**

   * Checked first few rows using `.head()`
   * Checked data types and null values with `.info()`
   * Summary statistics using `.describe()`
   * Frequency counts using `.value_counts()`

2. **Data Visualization:**

   * Histograms & Boxplots for distribution analysis (`Age`, `Fare`)
   * Scatterplots (`Age vs Fare`)
   * Pairplot to identify relationships between numeric features
   * Heatmap for correlation analysis

3. **Categorical Analysis:**

   * Countplots for `Sex` vs `Survived`
   * Countplots for `Pclass` vs `Survived`

4. **Observations & Insights:**

   * Females survived more than males
   * 1st class passengers had higher survival
   * Most passengers were aged 20–40 years
   * Fare positively correlated with survival
   * Key survival factors: Gender, Passenger Class, and Fare

---

## **Outcome**

* Gained practical experience in **exploratory data analysis**
* Learned to extract trends, relationships, and patterns from data
* Developed skills in **Python, Pandas, Matplotlib, and Seaborn**

---

## **How to Run**

1. Clone the repository.
2. Ensure `titanic.csv` is in the same folder.
3. Open `Task5_Titanic_EDA.ipynb` in **Jupyter Notebook**.
4. Run each cell to see **tables, graphs, and summary**.


