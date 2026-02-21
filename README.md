#  Python Data Cleaner

Python Data Cleaner is a **modular data preprocessing library** developed to handle common data cleaning, transformation, and preparation tasks required in data analysis and machine learning workflows.

This project was designed as a **publishable Python library** with a clean structure, reusable components, and unit tests for reliability.

---

##  Project Objective

The main objective of this project is to provide a **comprehensive and user-friendly Python library** for data preprocessing tasks, including:

- Data cleaning
- Data transformation
- Feature preparation
- Text and datetime processing

The library is suitable for academic use, personal projects, and machine learning pipelines.

---

##  Project Scenario

The library is intended to be used by data analysts and machine learning practitioners who need to preprocess raw datasets before analysis or model training.

Typical workflow:
1. Load a dataset
2. Apply preprocessing operations (e.g., missing value handling, scaling)
3. Transform and clean features
4. Use the processed data for analysis or modeling

---

##  Features

### 🔹 Data Cleaning
- Handle missing values (mean, median, constant, drop)
- Detect and clean outliers using IQR
- Filter rare categories

### 🔹 Data Transformation
- Min-Max normalization
- Standard scaling (z-score)
- Data type conversion (numeric, categorical)

### 🔹 Text Processing
- Text cleaning (lowercase, punctuation removal)
- Stopword removal
- Lemmatization (NLTK-based)

### 🔹 Categorical Encoding
- Label encoding
- One-hot encoding

### 🔹 Date & Time Handling
- Convert to datetime format
- Extract date features
- Detect and process datetime columns
- Clean invalid date values

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Unit Testing (pytest-style tests)

---

##  Library Structure

```text
data_cleaner/
│── __init__.py
│── missing_value_handler.py
│── outlier_handler.py
│── scaler.py
│── text_cleaner.py
│── categorical_encoder.py
│── data_type_converter.py
│── datetime_handler.py
│
tests/
│── test_missing_value_handler.py
│── test_outlier_handler.py
│── test_scaler.py
│── test_text_cleaner.py
│── test_categorical_encoder.py
│── test_data_type_converter.py
│── test_datetime_handler.py
│
main.py
