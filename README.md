# Titanic Exploratory Data Analysis (EDA)

<img width="1600" height="1088" alt="Titanic_dataset" src="https://github.com/user-attachments/assets/122fdd17-be06-491f-985d-113f763ffd77" />


## Objective

Perform Exploratory Data Analysis on the Titanic dataset to identify patterns, relationships, and factors affecting passenger survival.

## Tools Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

---

# Dataset Overview

## Dataset Information

### Observation

* The dataset contains passenger information such as age, gender, passenger class, fare, and survival status.
* Both numerical and categorical variables are present.
* Some columns contain missing values that may affect analysis.

---

## Statistical Summary

### Observation

* The average passenger age is around 30 years.
* Fare values vary considerably, indicating differences in ticket pricing.
* The large difference between minimum and maximum fare values suggests the presence of outliers.
* Passenger ages show a wide distribution across different age groups.

---

## Missing Values Analysis

### Observation

* Missing values are present in Age, Cabin, and Embarked columns.
* Cabin contains the highest number of missing records.
* Missing data should be considered before performing advanced modeling.

---

# Visualizations and Insights

## 1. Survival Distribution

<img width="1715" height="1361" alt="survival_count" src="https://github.com/user-attachments/assets/e3ec587f-f5dd-4e02-9974-45d88081c128" />


### Observation

* More passengers died than survived.
* Survival was not evenly distributed among passengers.
* The dataset contains a larger proportion of non-survivors.

---

## 2. Survival by Gender

<img width="1715" height="1361" alt="survival_gender" src="https://github.com/user-attachments/assets/157469a4-2501-4b93-ae8b-f6a20b0cb910" />


### Observation

* Female passengers had a much higher survival rate than male passengers.
* Gender appears to be one of the strongest factors affecting survival.
* Male passengers experienced a higher mortality rate.

---

## 3. Survival by Passenger Class

<img width="1715" height="1361" alt="survival_passenger" src="https://github.com/user-attachments/assets/7e3fe9c8-7417-49f5-b808-5a90cc5fd9da" />


### Observation

* First-class passengers had the highest survival rate.
* Third-class passengers experienced the highest mortality rate.
* Passenger class strongly influenced survival outcomes.

---

## 4. Age Distribution

<img width="2060" height="1407" alt="age" src="https://github.com/user-attachments/assets/3d979744-a548-49b8-82d9-5f0faa1d5097" />


### Observation

* Most passengers were between 20 and 40 years old.
* The distribution is slightly right-skewed.
* Very young and elderly passengers represent a smaller portion of the dataset.

---

## 5. Fare Distribution (Boxplot)

<img width="1919" height="1407" alt="Fare" src="https://github.com/user-attachments/assets/f35b92b2-b14d-4dc6-888f-555eefa7e57c" />


### Observation

* Several extreme fare values appear as outliers.
* Most passengers paid relatively low fares.
* A few passengers paid significantly higher ticket prices.

---

## 6. Correlation Heatmap

<img width="2330" height="2042" alt="correlation" src="https://github.com/user-attachments/assets/a7799dd7-c6fd-4e8d-88bf-9e83b004083b" />


### Observation

* Fare and passenger class show relationships with survival.
* Gender also demonstrates a notable relationship with survival.
* The heatmap helps identify correlations among numerical features.

---

## 7. Pairplot Analysis

<img width="2968" height="2958" alt="pairplot" src="https://github.com/user-attachments/assets/6d30383d-9c55-49b5-846e-2960b20c5287" />


### Observation

* Pairplot visualizes relationships among multiple numerical variables.
* Patterns can be observed between age, fare, passenger class, and survival.
* Useful for identifying trends, clusters, and possible correlations.

---

# Key Findings

1. Female passengers were more likely to survive than male passengers.
2. First-class passengers had the highest survival rates.
3. Most passengers belonged to the 20–40 age group.
4. Fare distribution contains notable outliers.
5. Passenger class and gender significantly influenced survival.
6. Missing values were mainly concentrated in the Cabin column.
7. Correlation analysis revealed relationships between fare, class, gender, and survival.

---

# Conclusion

The Exploratory Data Analysis of the Titanic dataset revealed important factors affecting passenger survival. Gender and passenger class emerged as the most influential variables. Visualizations such as histograms, boxplots, countplots, heatmaps, and pairplots helped uncover patterns, trends, and relationships within the dataset.
