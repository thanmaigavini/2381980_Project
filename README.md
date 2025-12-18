# Quantifying and Modelling Flood Impact on Populations and Infrastructure in England

This repository contains the code, data, and supporting materials for the MSc dissertation **"Quantifying and Modelling Flood Impact on Populations and Infrastructure in England"**, submitted to the **University of Bristol** in December 2024.

The project integrates **machine learning**, **geospatial analysis**, and **socio-economic deprivation data** to assess flood risk and vulnerability across **267 Local Administrative Districts (LADs) in England**.

---

## 📌 Project Overview

Flooding is a major environmental and socio-economic challenge in England, with impacts that disproportionately affect vulnerable populations. This project develops a **data-driven framework** to:

- Quantify populations and properties exposed to flood risk  
- Measure socio-economic vulnerability using a **Social Vulnerability Index (SVI)**  
- Model flood impact levels on populations and residential infrastructure using a **Random Forest Classifier (RFC)**  
- Visualize results through **interactive geospatial maps**  

The framework supports **policy-making, urban planning, and disaster risk reduction**.

---

## 🎯 Objectives

1. Quantify flood risk for people and properties across England  
2. Characterize socio-economic vulnerability using deprivation and demographic indicators  
3. Predict flood impact levels on:
   - Populations
   - Residential infrastructure  
4. Visualize spatial patterns of risk and vulnerability using interactive maps  

---

## 📂 Repository Structure

```
├── 2381980_CODE.ipynb          # Main Jupyter Notebook (analysis and models)
├── flood risk data_new.xlsx   # Flood risk indicators
├── IMD_L1.xlsx                # Index of Multiple Deprivation data
├── IMD_L1.geojson             # Geographic boundaries
└── README.md                  # Project documentation
```

---

## 🛠️ Methods & Technologies

### Tools & Libraries
- Python
- Jupyter Notebook
- Pandas, NumPy
- GeoPandas
- Matplotlib, Seaborn
- Scikit-learn
- Folium
- QGIS

### Machine Learning
- **Model:** Random Forest Classifier  
- **Validation:** Stratified K-Fold Cross Validation  
- **Accuracy:**
  - Population impact model ≈ **0.80**
  - Residential property impact model ≈ **0.93**

---

## 🗺️ Outputs

- Choropleth maps showing:
  - People and properties at risk
  - Social Vulnerability Index (SVI)
  - Demographic flood vulnerability
  - Flood impact levels
- Interactive maps with tooltips and selectable layers

---

## 👤 Author

**Thanmai Gavini**  
MSc Engineering Mathematics  
University of Bristol  

Supervisor: **Prof. Leon Danon**

---

## 📜 License

This project is provided for **academic and research purposes only**.
