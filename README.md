# 🏥 Hospital Readmission Prediction – NHS Aligned ML Project

This project uses a Random Forest model to predict hospital readmissions using structured patient data (e.g. age, medication count, A1C results).

## 📦 Tools Used
- Python
- pandas
- scikit-learn
- matplotlib
- Jupyter Notebook

### 🧠 Objective
To simulate how machine learning can be used in healthcare for early identification of at-risk patients, improving clinical outcomes and resource efficiency — aligning with NHS digital health goals.

### 🔧 Key Steps
1. Data loading and inspection
2. Encoding categorical variables
3. Splitting data into training and test sets
4. Model training with Random Forest
5. Evaluation using confusion matrix & classification report
6. Visualising top predictors of readmission

### 📊 Feature Importance Example
![Feature Importance] (Images\feature-importance.png)

### 🗂️ File Structure
- `Notebooks\readmission_analysis.ipynb` – Main notebook
- `Data\sample_hospital_readmissions.csv` – Input data
- `README.md` – Project overview

### 🚀 How to Run
```bash
pip install pandas scikit-learn matplotlib
