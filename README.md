# Earthquake Prediction Using Time Series Data

This project predicts earthquake magnitudes using machine-learning models trained on structured time-series data.  
It explores traditional regression models and ensemble learning techniques to understand how well machine-learning can approximate seismic behavior.

The work is implemented in the notebook:
**Earthquake_prediction_using_Time_Series_Data.ipynb**

---

## 📌 Project Overview

Earthquake magnitude prediction is a challenging time-series regression problem.  
This project builds a complete workflow:

- Data loading and preprocessing  
- Feature engineering  
- Train–test splitting  
- Multiple regression models  
- Performance evaluation (MSE, MAE, RMSE, R²)  
- Visualization of model predictions  
- Interpretation using feature importance  

The goal is to compare how different models perform on seismic time-series data and identify the most reliable baseline.

---

### 📂 Dataset

This project uses a publicly available earthquake magnitude dataset:

### **Dataset Link (Kaggle):**  
🔗 https://www.kaggle.com/datasets/danielbaires34/earthquake-dataset

This dataset includes:

- Earthquake magnitude  
- Depth  
- Latitude, longitude  
- Time of occurrence  
- Optional derived features you can compute (rolling mean, lag features, etc.)

You can replace this dataset with any seismic CSV file having:

- A timestamp or sequential index  
- Magnitude column (target variable)  
- Additional numerical predictors (optional)
---

## 🧠 Models Used

### **1. Linear Regression**
Baseline model to check linear relationships.

### **2. Support Vector Regression (SVR)**
RBF kernel used for non-linear pattern capture.

### **3. Random Forest Regressor**
Ensemble model — typically the strongest performer on mixed numerical features.

Used with:
- 100 estimators  
- Random seed for reproducibility  
- CPU-friendly configuration  

---

## 📊 Evaluation Metrics

The following regression metrics are used:

| Metric | Meaning |
|--------|---------|
| **MSE** | Squared error (penalizes large mistakes) |
| **RMSE** | Square-root of MSE |
| **R² Score** | How well the model explains variance |



## Requirements

```pip install numpy pandas scikit-learn matplotlib```


   

