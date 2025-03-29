# Network Traffic Anomaly Detection Using Machine Learning

This repository contains the complete implementation of a machine learning project for detecting anomalies in network traffic, leveraging the UNSW-NB15 dataset.

Dataset Sourced from: https://www.kaggle.com/datasets/mrwellsdavid/unsw-nb15/data

---
## 👥 Contributors

Ivan Leonychev (T00727314)
- Data preprocessing, feature engineering, model implementation, documentation, and GitHub management.

Polina Kniazeva (T00704993)
- Initial dataset analysis, exploratory data analysis, model training, evaluation, and visualization.

---

## 📌 Project Overview

The project aims to detect network anomalies through supervised machine learning techniques, specifically comparing the effectiveness of Random Forest and XGBoost classifiers.

---

## 📂 Repository Structure

- **datasets/**  
  Contains the original UNSW-NB15 training dataset (testing set is too big, pls download directly from the source).

- **notebooks/**  
  Jupyter Notebooks detailing each step of the project:
  - `01_Data_Exploration.ipynb`: Exploratory data analysis and visualization.
  - `02_Data_Preprocessing.ipynb`: Feature engineering, data cleaning, and transformation steps.
  - `03_Model_Training_and_Evaluation.ipynb`: Training, evaluation, and visual comparison of ML models.

- **reports/**  
  Final project documentation and detailed report.

---

## 🚀 Getting Started (Setup & Installation)

### Step 1: Clone Repository
```bash
git clone [https://github.com/zeinhord/network-anomaly-detection.git]
cd network-anomaly-detection
```

### Step 2: Install Dependencies
```bash
pip install -r requirements.txt
```

## 🔧 Executing the Project

You can run each Jupyter Notebook in the following order:

### Step 1: Data Exploration
```bash
jupyter notebook notebooks/01_Data_Exploration.ipynb
```

### Step 2: Data Preprocessing
```bash
jupyter notebook notebooks/02_Data_Preprocessing.ipynb
```

### Step 3: Model Training and Evaluation
```bash
jupyter notebook notebooks/03_Model_Training_and_Evaluation.ipynb
```
