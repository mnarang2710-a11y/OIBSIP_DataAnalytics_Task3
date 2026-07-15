# OIBSIP_DataAnalytics_Task3
# 🧹 Task 3: Data Cleaning & Preprocessing

## 📌 Objective

The objective of this task is to demonstrate professional-level data cleaning skills by transforming a messy dataset into a clean, consistent, and analysis-ready dataset. The workflow focuses on identifying and resolving data quality issues while documenting every cleaning decision to ensure transparency and reproducibility.

---

## 🛠️ Tools & Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy

---

## 📂 Dataset

- **Dataset:** messy_customer_data.csv
- **File Format:** CSV
- **Purpose:** Data Cleaning & Preprocessing
- **Output:** Cleaned dataset ready for analysis

---

## 🔍 Steps Performed

### 1. Data Loading & Quality Assessment
- Imported the dataset into Jupyter Notebook.
- Examined dataset dimensions and structure.
- Generated a comprehensive data quality report including:
  - Missing values per column
  - Duplicate records
  - Data types
  - Statistical summary
  - Value range anomalies

### 2. Missing Data Handling
Applied suitable techniques for handling missing values based on the nature of each column:

- Mean imputation for normally distributed numerical columns.
- Median imputation for skewed numerical columns.
- Mode imputation for categorical variables.
- Row deletion where missing values were minimal and did not significantly impact the dataset.

Each strategy was selected to preserve data quality while minimizing information loss.

### 3. Duplicate Removal
- Identified duplicate records.
- Removed duplicate rows from the dataset.
- Documented the total number of duplicates removed.

### 4. Data Standardization
Standardized inconsistent data formats by:

- Converting text values to a consistent format.
- Normalizing categorical values (e.g., Male, male, M → Male).
- Removing unnecessary spaces.
- Standardizing date columns using datetime format.
- Ensuring consistent naming conventions.

### 5. Outlier Detection & Treatment
- Applied the **Interquartile Range (IQR)** method to detect outliers in numerical features.
- Evaluated each detected outlier.
- Removed or retained outliers based on their business significance.
- Documented the reasoning behind each decision.

### 6. Data Type Correction
Corrected inappropriate data types by converting:

- Date columns → Datetime
- ID columns → String/Object
- Monetary values → Float
- Numerical attributes → Integer or Float where applicable

### 7. Before vs After Comparison
Prepared a summary comparison including:

- Total rows
- Total columns
- Missing value count
- Duplicate count
- Data type accuracy
- Dataset readiness

This comparison clearly demonstrates the improvements achieved during preprocessing.

### 8. Exporting the Clean Dataset
- Saved the cleaned dataset as a new CSV file.
- Verified successful export for future analysis and machine learning tasks.

---

## 📈 Data Quality Improvements

The following quality issues were addressed during preprocessing:

- ✅ Missing values handled
- ✅ Duplicate records removed
- ✅ Inconsistent text formatting standardized
- ✅ Date formats corrected
- ✅ Data types corrected
- ✅ Outliers identified and treated
- ✅ Dataset validated for further analysis

---

## ✅ Outcome

The dataset was successfully transformed into a clean and analysis-ready format by resolving missing values, removing duplicates, correcting inconsistencies, handling outliers, and standardizing data types. The cleaned dataset is reliable, consistent, and suitable for exploratory data analysis, visualization, and machine learning applications.

---

## 🚀 Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Missing Value Treatment
- Duplicate Detection & Removal
- Data Standardization
- Outlier Detection (IQR Method)
- Data Type Conversion
- Data Validation
- Feature Preparation
- Pandas & NumPy
- Python Programming

---

## 👨‍💻 Author

**Manish**

Data Analytics Intern  
OASIS INFOBYTE 
