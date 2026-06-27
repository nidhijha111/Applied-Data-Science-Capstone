# 🚀 Applied Data Science Capstone – SpaceX Falcon 9 Landing Prediction

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![IBM](https://img.shields.io/badge/IBM-Applied%20Data%20Science-blue)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-success)
![Plotly](https://img.shields.io/badge/Plotly-Dash-orange)
![Folium](https://img.shields.io/badge/Folium-Maps-brightgreen)

## 📌 Project Overview

This project was completed as part of the **IBM Applied Data Science Capstone** course. The objective is to analyze historical **SpaceX Falcon 9** launch data and build machine learning models capable of predicting whether the **first-stage booster** will successfully land.

Reusable rockets significantly reduce launch costs. Accurate prediction of landing success provides valuable insights into launch planning, mission analysis, and cost estimation.

---

# 🎯 Problem Statement

SpaceX has revolutionized the aerospace industry through reusable launch vehicles. The ability to predict whether a Falcon 9 first-stage booster will land successfully helps estimate launch costs and identify mission characteristics associated with successful recoveries.

This project applies the complete Data Science lifecycle to solve this prediction problem.

---

# 📚 Project Workflow

```text
Business Problem
        │
        ▼
Data Collection
        │
        ▼
Data Wrangling
        │
        ▼
Exploratory Data Analysis
        │
        ▼
SQL Analysis
        │
        ▼
Interactive Visual Analytics
        │
        ▼
Machine Learning
        │
        ▼
Model Evaluation
        │
        ▼
Business Insights
```

---

# 📂 Project Structure

```text
Applied-Data-Science-Capstone/
│
├── Data Collection
│   ├── SpaceX API Notebook
│   ├── Web Scraping Notebook
│
├── Data Wrangling
│
├── Exploratory Data Analysis
│   ├── Data Visualization
│   ├── SQL Analysis
│
├── Interactive Visual Analytics
│   ├── Folium Maps
│   ├── Plotly Dash
│
├── Predictive Analysis
│   ├── Machine Learning Models
│
├── Data
│
├── Presentation
│
└── README.md
```

---

# 📊 Dataset

The project combines data collected from:

* SpaceX REST API
* Wikipedia Launch Records

The final dataset includes attributes such as:

* Flight Number
* Launch Date
* Launch Site
* Booster Version
* Payload Mass
* Orbit
* Landing Outcome
* Landing Success Class

---

# ⚙️ Technologies Used

## Programming

* Python

## Data Analysis

* Pandas
* NumPy

## Data Visualization

* Matplotlib
* Seaborn

## SQL

* SQLite
* SQL

## Interactive Analytics

* Folium
* Plotly Dash

## Machine Learning

* Scikit-learn

---

# 🔬 Methodology

## 1. Data Collection

Launch information was retrieved from the official SpaceX REST API and supplemented using web scraping techniques from Wikipedia.

---

## 2. Data Wrangling

The collected datasets were cleaned and transformed by:

* Handling missing values
* Removing duplicates
* Standardizing formats
* Feature engineering
* Creating target labels

---

## 3. Exploratory Data Analysis

Multiple visualizations were created to identify relationships between mission variables and landing success.

Examples include:

* Flight Number vs Success
* Payload Mass vs Success
* Launch Site Analysis
* Orbit Analysis
* Yearly Success Trend

---

## 4. SQL Analysis

SQL queries were performed to answer business questions such as:

* Which launch sites had the highest success rate?
* What payloads were associated with successful launches?
* Which launch sites handled the largest payloads?
* How did launch performance change over time?

---

## 5. Interactive Visual Analytics

### Folium

Interactive maps were developed to visualize:

* Launch sites
* Successful landings
* Failed landings
* Proximity to infrastructure

### Plotly Dash

Interactive dashboards allow users to:

* Filter launch sites
* Filter payload ranges
* View launch success pie charts
* Analyze payload versus launch outcome

---

## 6. Machine Learning

Classification models were trained to predict landing success.

Models evaluated include:

* Logistic Regression
* Support Vector Machine (SVM)
* Decision Tree
* K-Nearest Neighbors (KNN)

Hyperparameter tuning was performed using GridSearchCV to improve model performance.

---

# 📈 Key Findings

* Launch site significantly influences landing success.
* Payload mass affects landing outcomes.
* Launch success has improved over time.
* Orbit selection contributes to mission success.
* Interactive dashboards improve exploration of launch performance.
* Machine learning models can effectively predict landing success using historical launch characteristics.

---

# 🎯 Skills Demonstrated

* Data Collection using APIs
* Web Scraping
* Data Cleaning
* Feature Engineering
* Exploratory Data Analysis
* SQL
* Interactive Dashboard Development
* Geospatial Visualization
* Machine Learning
* Model Evaluation
* Business Insight Generation

---

# 📷 Project Deliverables

* Data Collection Notebooks
* Data Wrangling Notebook
* EDA Visualization Notebook
* SQL Notebook
* Folium Map
* Plotly Dash Dashboard
* Machine Learning Notebook
* Final Presentation
* Final Project Report

---

# 🚀 Future Improvements

Future enhancements may include:

* Real-time launch prediction using live SpaceX APIs.
* Deployment of the prediction model as a web application.
* Integration of weather and telemetry data.
* Evaluation of ensemble learning techniques.
* Automated model retraining using updated launch records.

---

# 👨‍💻 Author

**Nidhi Kumari**

IBM Applied Data Science Capstone Project

---

# 📜 License

This repository is intended for educational purposes as part of the IBM Applied Data Science Capstone course.
