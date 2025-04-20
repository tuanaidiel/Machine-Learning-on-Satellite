# Machine-Learning-on-Satellite

## 📊 Project Overview

This capstone project explores how satellite attributes such as purpose, country of contractor, launch vehicle, mass, and power consumption influence the expected lifespan and operational performance of satellites. The project applies machine learning techniques to develop predictive models that assist in forecasting satellite longevity, supporting better decision-making for investments and design optimizations in the aerospace industry.

## 🧠 Project Objectives

### 🔍 Data Analysis
- Analyze average satellite lifetime based on purpose
- Identify countries with the longest-living satellites
- Assess launch vehicles by average satellite lifespan
- Explore relationships between satellite mass and lifespan
- Explore relationships between power consumption and lifespan
- Conduct financial analysis on mass/power vs. lifespan

### 🤖 Machine Learning Models
- **Linear Regression**: Predict satellite lifetime from power consumption
- **Logistic Regression**: Classify if lifetime > 10 years based on power
- **K-Nearest Neighbors (KNN)**: Categorize satellites into power groups based on purpose
- **Random Forest Classifier**: Predict satellite purpose from specs
- **K-Means Clustering**: Group satellites by mass, power, contractor, and lifespan

## 🧩 Problem Statement

Despite significant investments in satellite development, many organizations lack predictive insight into what factors most influence satellite longevity. This project uses data-driven approaches to model and analyze satellite characteristics, enabling more informed decisions regarding design, operation, and investment.

## 📂 Dataset Description

| Feature | Description |
|--------|-------------|
| `Satellite` | Name or identifier of the satellite |
| `Purpose` | Primary mission (e.g., Communication, Earth Observation) |
| `Country of Contractor` | Country responsible for construction or launch |
| `Launch Vehicle` | Vehicle used to launch the satellite |
| `Mass (kg)` | Weight of the satellite |
| `Power (Watts)` | Power consumption for operation |
| `Expected Lifetime (Years)` | Target operational lifespan of the satellite |

## 🛠️ Technologies Used
- Python
- Pandas, Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## 📈 Visualizations
- Bar charts for country-wise lifetime
- Scatter plots for mass vs. lifetime
- Correlation heatmaps
- Distribution plots for satellite categories

## 📚 Business Value

This project delivers predictive models and insights that support:
- Improved satellite design based on lifetime indicators
- Better financial planning for satellite programs
- Strategic launch vehicle and contractor selection
- Market positioning in the space tech sector

## 👤 Author

**Tuan Muhammad Aidiel bin Tuan Kamazon**  
Capstone 3 - Business Role  
Group 1

---

Feel free to clone or fork the repository and explore the analysis!
