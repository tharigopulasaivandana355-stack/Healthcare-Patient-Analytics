# 🏥 Healthcare Patient Analytics

## 📌 Project Overview
This project analyzes patient health data to explore the relationship between **diabetes status, blood pressure, body mass index (BMI), and age groups**.  
The work combines **Python (Jupyter Notebook)** for data preprocessing & exploratory analysis with **Tableau** for interactive dashboards.

---

## 🔑 Key Features
- **Data Cleaning & Standardization**:
  - Standardized columns for Age, Gender, BMI, Glucose, Blood Pressure, Diabetes Outcome
  - Derived fields: Age Group, BMI Category, Blood Pressure Category
- **KPIs**:
  - Total patients
  - Percentage of diabetic vs non-diabetic
  - Distribution by BMI & Blood Pressure categories
- **Visualizations**:
  1. Diabetic vs Non-Diabetic patient counts
  2. Patient summary by Blood Pressure category
  3. Patient distribution by BMI category
  4. Average BMI by Age Group
  5. Patients by Blood Pressure × Diabetes status
- **Exports**: Clean summary CSVs prepared for Tableau dashboards

---

## 📂 Repository Structure
```
Healthcare-Patient-Analytics/
│── data/                          # Original dataset (Healthcare Data.xlsx)
│── exports/                       # Clean CSVs for Tableau
│── tableau/                       # Tableau workbook (.twbx) + screenshots
│── Healthcare_Patient_Analytics.ipynb   # Jupyter Notebook
│── README.md                      # Project description (this file)
```

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Healthcare-Patient-Analytics.git
   cd Healthcare-Patient-Analytics
   ```
2. Install requirements:
   ```bash
   pip install pandas matplotlib openpyxl
   ```
3. Place dataset in `data/Healthcare Data.xlsx`
4. Run the notebook:
   ```bash
   jupyter notebook Healthcare_Patient_Analytics.ipynb
   ```
5. Open the Tableau workbook (`.twbx`) to explore dashboards.

---

## 📊 Tableau Dashboards
Screenshots of dashboards created in Tableau:

- **Diabetic vs Non-Diabetic Patients**
- **Patients by Blood Pressure Category**
- **BMI Category Distribution**
- **BMI by Age Group**
- **BP × Diabetes Status Heatmap**

*(add images from `tableau/` here)*

---

## 📚 Dataset
- **Source**: Healthcare Data.xlsx  
- Contains patient demographics and health metrics including Age, Gender, BMI, Glucose, Blood Pressure, and Diabetes Outcome.  
- Size: 768 patients × 9 columns.

---


