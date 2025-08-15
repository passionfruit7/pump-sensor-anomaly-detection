# ANOMALY DETECTION IN TIME SERIES PUMP SENSOR DATA

![Python](https://img.shields.io/badge/Python-3.10-blue.svg)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-KMeans%20%7C%20Isolation%20Forest-brightgreen.svg)
![Time Series](https://img.shields.io/badge/Time%20Series-Analysis-orange.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Active-success.svg)

---

## 📌 Introduction
Industrial pump systems generate large volumes of sensor data daily. Detecting unusual patterns early can prevent costly breakdowns, improve safety, and reduce downtime.  

This project applies **unsupervised anomaly detection** to multivariate time series data using **KMeans clustering** and **Isolation Forest** for predictive maintenance and fault detection.

---

## 📂 Overview
**Workflow Steps:**
1. **Data Preparation** – Clean sensor readings, handle missing values, scale features  
2. **Stationarity Analysis** – Apply Augmented Dickey-Fuller (ADF) test to assess time series properties  
3. **Dimensionality Reduction** – Use PCA for visualization and reduced feature space  
4. **Anomaly Detection**
   - **KMeans**: Detect outliers by distance from cluster centers  
   - **Isolation Forest**: Identify anomalies via isolation-based tree structures  
5. **Evaluation** – ROC curves, AUC, precision, recall, F1-score, confusion matrices  
6. **Interpretability** – Plot anomaly scores and thresholds

---

## 📊 Results

**1. ROC Curves**

<img width="567" height="455" alt="image" src="https://github.com/user-attachments/assets/78a6d5d3-8a77-4a4f-8da1-f0522d252ef0" />


**2. Anomaly Scores Over Time**

<img width="1190" height="790" alt="image" src="https://github.com/user-attachments/assets/4091ef6e-fa28-4026-a14b-ce414663f5ef" />


---

## 🚀 Applications
-  Predictive maintenance in industrial systems  
-  Early detection of equipment faults  
-  Monitoring complex sensor networks for abnormal behavior  

---

## 🛠 Tech Stack
- **Language:** Python 3.10  
- **Libraries:** Pandas, NumPy, Scikit-learn, Statsmodels, Matplotlib, Seaborn
