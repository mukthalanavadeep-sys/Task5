# Task5#  Titanic Dataset - Exploratory Data Analysis (EDA)

##  Project Overview
This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to understand patterns, trends, and relationships between different features such as survival, age, gender, and passenger class.

---

##  Objective
To analyze the Titanic dataset using statistical summaries and visualizations in order to identify:
- Patterns
- Trends
- Relationships
- Outliers

---

##  Tools & Technologies Used
- Python
- Google Colab
- Pandas
- Seaborn
- Matplotlib

---

##  Dataset Description
The dataset contains information about Titanic passengers such as:
- PassengerId
- Survived
- Pclass
- Name
- Sex
- Age
- SibSp
- Parch
- Fare
- Embarked

---

##  Steps Performed

### 1. Data Loading
- Loaded dataset using Pandas
- Displayed first 5 rows using head()

### 2. Data Exploration
- Used info() to check structure of data
- Used describe() for statistical summary
- Checked missing values using isnull().sum()

### 3. Data Cleaning
- Filled missing values in:
  - Age → mean
  - Fare → mean
  - Embarked → mode
- Removed Cabin column due to many missing values

---

##  Visualizations Used

- Countplot → Survival Count
- Countplot → Gender vs Survival
- Histogram → Age Distribution
- Boxplot → Age Outliers
- Heatmap → Correlation Matrix

---

##  Key Insights

- Majority of passengers did not survive
- Females had higher survival rate than males
- Most passengers were between 20–40 years old
- Passenger class affected survival rate
- Age contains outliers

---

##  Conclusion
EDA helped understand survival patterns and relationships in the Titanic dataset. Visualizations made it easier to identify trends and insights.

