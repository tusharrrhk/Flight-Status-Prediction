# Flight Status Prediction

  This project aims to uncover key patterns and insights from flight data to enhance operational efficiency and improve passenger experience. It also aims in developing Machine Learning models on a multi-class classificiation dataset to make a prediction.
  <p align="center">
  <img src="Logo.webp" alt="Company Logo" width="350">


---

## 📊 **Project Overview**

This analysis gives you a detailed understanding into:
- Analyzing flight data to identify trends and patterns.
- Exploring seasonal, daily, and hourly variations in flight operations.
- Evaluating performance based on departure and arrival status.
- Provide actionable recommendations to optimize operations.
- Create visualizations to aid data-driven decision-making.
- Developing ML models like Random Forest and XGBoost to predict arrival status.
- Improve the performance by using K-Fold Cross Validation and Hyperparameter Tuning.

---

## 📂 **Dataset**
This dataset has been fetched from <a href="https://www.kaggle.com/datasets/mahoora00135/flights/data">Kaggle</a> which contains around 336k rows and 21 columns. The dataset contains information on flight schedule, delays, carrier,  flight origin and destination from the year 2013. The dataset was cleaned by handling data inconsistencies. Columns were standardized for consistency. Feature engineering was performed to create meaningful variables for analysis.

---

## 🛠️ **Features**
- Comprehensive data preprocessing and cleaning.
- Exploratory data analysis to identify trends.
- Imbalance handling and feature selection.
- Visual representation of key findings.
- Actionable insights and strategic recommendations.
- Handle imbalance dataset by using upsampling technique SMOTE.
- Enhance the metric by using different parameters.

---

## 🚀 **Key Insights**

- Q3 had the highest number of flights, with July being the busiest month.
- EWR airport had the highest traffic compared to JFK and LGA.
- Morning and afternoon were the busiest departure times.
- Most flights arrived earlier than scheduled, with significant delays observed.
- Top destinations include ORD, ATL, LAX, BOS, and MCO.

For a detailed list of insights, refer to the [Insights document](./Insights.md).

---

## 📌 **Recommendations**

- Optimize staffing and resources during Q3 and peak hours.
- Implement measures to reduce delays at EWR airport.
- Schedule flights strategically to reduce congestion during peak times.
- Enhance customer communication regarding anticipated delays.
- Leverage data analytics for proactive decision-making.

For a detailed list of recommendations, refer to the [Recommendations document](./Recommendations.md).

---

## 🎯 **Results**

- Random Forest : 58%
    - With Hyperparameter Tuning : 42%

- XGBoost : 65%
    - With Hyperparameter Tuning : 68%

