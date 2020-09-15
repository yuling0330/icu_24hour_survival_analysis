# icu_24hour_survival_analysis
----
## Background

**Industry Overview**: 

MIT's GOSSIS community initiative is seeking an efficient way to address the problems with existing severity of illness systems: 
They often lack generalizability beyond the patients on whom the models were developed, and
The models are often proprietary, costly to use (APACHE scoring system…), and suffer from opaque algorithms. 


----
### Objective:

Create a model that uses data from the first 24 hours of intensive care to predict patient survival with:  Better prediction probability of death (as compared to apache_4a_icu_prob, apache_4a_hospital_prob)
  - Minimize apache features 
  - Transparent (easy to explain)
  - Generalizability
  - Less complexity

----
### Data:

The dataset contains 90k patients, with 186 features, among 147 hospitals and 5 countries
Download: https://www.kaggle.com/c/widsdatathon2020/data

----
### Exploratory Data Analysis:

<p align="center">
  <img src="https://github.com/yuling0330/icu_24hour_survival_analysis/blob/master/presentation/eda_to_show.png" />
</p>

----
### Models:

- Logistic Regression
- Logistic Regression with PCA
- Random Forest
- Catboost
- Light Gradient Boost

----
### Results:


<p align="center">
  <img src="https://github.com/yuling0330/icu_24hour_survival_analysis/blob/master/presentation/results_to_show.PNG" />
</p>
