Title: Employee Attrition Analytics (HR / People Analytics)
**Overview**

In this project, I dug into the IBM HR dataset to figure out why employees leave and to predict who’s likely to go next. I used a mix of data exploration, statistical tests, and logistic regression. I pulled all this together in Power BI dashboards, so HR teams get clear, usable insights they can actually act on.

**Objectives**

Find out what really drives employee attrition
Build a predictive model that’s easy to understand
Sort employees into Low, Medium, and High attrition risk groups
Turn model results into a practical dashboard for HR decisions

**How I Did It**
1. **Data Preparation**
Cleaned and prepped the data with Pandas
Encoded categorical columns so the model could read them
Split data into train and test sets, making sure the split was balanced
Scaled features for better logistic regression performance

2. **Modelling**
Trained a logistic regression model (used balanced class weights)
Scored about 0.80 ROC-AUC
Dug into model coefficients and odds ratios to explain what’s driving predictions

**3. Risk Segmentation**
Turned model probabilities into three groups: Low, Medium, and High Risk. This helps HR zero in on who needs attention—before they think about leaving.

**Dashboards**

Descriptive HR Insights

See overall attrition rates
Break down attrition by department
Spot the effect of overtime
Compare satisfaction and income levels
Analyze tenure patterns

Predictive Risk Segmentation

Visualize how risk is spread across the workforce
See which departments are at higher risk
Drill down to employee-level risk, with easy-to-read formatting

**Tools Used**
Python: Pandas, NumPy, Scikit-learn
Power BI: DAX, data modelling
<img width="856" height="873" alt="Dashboard_Predictive_Risk" src="https://github.com/user-attachments/assets/358a842b-310a-4bd2-b907-c4af512d14fb" />
<img width="856" height="874" alt="Dashboard_Descriptive" src="https://github.com/user-attachments/assets/93b91d5b-29de-42ce-805d-c662ef83964b" />
[Attrition Project.pdf](https://github.com/user-attachments/files/25682015/Attrition.Project.pdf)
