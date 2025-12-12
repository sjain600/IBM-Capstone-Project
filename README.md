# 🚀 SpaceY Launch Intelligence  
*A data science project for SpaceY — the bold new challenger to SpaceX*

## 🛰️ Project Overview  
SpaceY is the newest entrant in the private spaceflight race, founded by the visionary billionaire industrialist **Allon Musk**. As part of the data science team, the mission is clear:  
**Understand SpaceX. Outperform SpaceX. Compete with SpaceX.**

This project focuses on analyzing open data from the official SpaceX API to uncover insights about launch pricing, rocket performance, and first-stage reusability.

## 🎯 Objectives  
### 1. **Predict Launch Prices**  
SpaceX doesn’t publicly reveal detailed launch pricing formulas—so we reverse-engineer it.  
Using historical launch data, payload mass, orbit type, launch site, and other technical features, we build data-driven pricing intelligence dashboards for SpaceY’s strategy team.

### 2. **Model First-Stage Reusability**  
Rather than diving into rocket science and engineering equations, we take a data-first approach:  
Train a machine learning model that predicts whether SpaceX will **successfully reuse the first stage** of its Falcon rockets.  
The model uses publicly available launch records, landing attempts, booster history, and mission attributes.

### 3. **Build Dashboards for Internal Teams**  
Interactive visual dashboards communicate:  
- Launch success trends  
- Booster reuse patterns  
- Key variables influencing launch price  
- Predictions from the trained ML model  

These will help SpaceY craft competitive pricing strategies and understand where SpaceX gains efficiency.

## 📦 Key Components  
- **Data Extraction:** Live pull from the SpaceX REST API  
- **Data Wrangling & Feature Engineering:** Cleaning, structuring, encoding and enriching launch data  
- **Machine Learning:** Binary classification model predicting first-stage reuse  
- **Visualization:** Interactive dashboards (plotly, dash, tableau, or streamlit) for decision-makers  
- **Insights Report:** Strategic findings on SpaceX’s operational patterns

## 🧠 Machine Learning Model  
The core ML pipeline includes:  
- Exploratory data analysis (EDA)  
- Feature selection around mission type, orbit, payload, landing type, booster history, etc.  
- Training and evaluation of multiple algorithms  
- Final deployment-ready model for reuse prediction  

## 📊 Dashboards  
Dashboards will highlight:  
- Price estimation logic  
- Booster performance timelines  
- Mission difficulty factors  
- Predicted vs. actual reuse outcomes

## 🌌 Why This Matters for SpaceY  
Understanding a competitor’s strengths is the first step toward outperforming them.  
This project gives SpaceY:  
- Clear intelligence on the economics of rocket launches  
- A predictive lens on operational success factors  
- Data-driven foundations for its own launch strategy

## 🛠️ Tech Stack  
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Plotly / Dash / Streamlit  
- REST APIs  
- Jupyter Notebooks  

## 📁 Repository Structure  
