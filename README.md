# Employees_Attrition_Prediction
Data science Captone (cohort 7): Employee Attrition Prediction using Machine Leraning
# Employee Attrition Prediction using Machine Learning

## 📌 Project Overview
This project was completed as part of the Data Science Capstone (Cohort 7). The objective is to build a machine learning model that predicts whether an employee is likely to leave the company (Attrition) based on employee-related features.

## 🎯 Objectives
- Perform exploratory data analysis (EDA).
- Prepare and preprocess the dataset.
- Build and compare multiple machine learning models.
- Evaluate model performance using classification metrics.
- Recommend the best model for employee attrition prediction.

## 📂 Dataset
- IBM HR Analytics Employee Attrition Dataset
- Target variable: **Attrition**
  - Yes = Employee leaves
  - No = Employee stays

## 🛠️ Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 📊 Exploratory Data Analysis (EDA)
The following analyses were performed:
- Data quality assessment
- Missing value check
- Duplicate check
- Univariate analysis
- Boxplots for outlier detection
- Count plots
- Histograms
- Correlation analysis (if applicable)

## 🤖 Machine Learning Models
The following models were trained and evaluated:
- Logistic Regression
- Logistic Regression (Balanced)
- Decision Tree
- Decision Tree (Balanced)
- Random Forest
- Random Forest (Balanced)

GridSearchCV was used to tune the Logistic Regression model.

## 📈 Evaluation Metrics
The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion Matrix

## 🏆 Results
Among all the models, **Balanced Logistic Regression** achieved the best overall performance with the highest ROC-AUC score (0.693). It also improved the detection of employees likely to leave, making it the recommended model for employee attrition prediction.

## 📁 Repository Structure

```
Employees_Attrition_Prediction/
│── Employee_Attrition.ipynb
│── README.md
│── requirements.txt
│── images/
│── presentation/
│── LICENSE
│── .gitignore
```

## 🚀 How to Run the Project
1. Clone the repository.
2. Install the required libraries:
   ```
   pip install -r requirements.txt
   ```
3. Open the notebook:
   ```
   Employee_Attrition.ipynb
   ```
4. Run all cells from top to bottom.

## 👨‍💻 Author

**Najeemdeen Usein Oladimeji**

B.Sc. Statistics

Data Analyst | Machine Learning Enthusiast
