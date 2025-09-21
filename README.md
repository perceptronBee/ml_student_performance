# Student Performance Analysis and Prediction

This notebook analyzes the **Student Performance dataset** from Kaggle and applies a **Linear Regression model** to predict student scores based on various factors such as study hours, previous scores, and extracurricular activities.

## Dataset
Dataset: "Student Performance Dataset" from Kaggle  
URL: https://www.kaggle.com/datasets/nikhil7280/student-performance-multiple-linear-regression/data  

The dataset contains multiple features related to student performance:

- `Previous Score` : Student’s score in the previous exam
- `Hours Studied` : Number of hours studied
- `Extracurricular Activities` : Participation in extracurricular activities (Yes/No)
- `Performance Index` : Target variable representing the current performance

## Notebook Contents
1. **Exploratory Data Analysis (EDA)**  
   - Overview of dataset (`df.head()`, `df.describe()`)  
   - Distribution and correlation plots  
   - Boxplots and scatter plots for feature analysis

2. **Data Preprocessing**  
   - Encoding categorical variables  
   - Handling missing values and outliers

3. **Modeling**  
   - Linear Regression  
   - Train-test split and model evaluation using **R²**, **MSE**, and **MAE**

4. **Results**  
   - Comparison of model performances  
   - Observed R² score: Linear Regression ≈ 0.98

## How to Use
1. Clone the repository:  
```
git clone https://github.com/yourusername/student-performance-analysis.git
```

2. Open the notebook in Jupyter or VSCode:  
```
jupyter notebook student_performance_analysis.ipynb
```

3. Run all cells to reproduce the analysis and results.

## Notes
This is a first exploratory project, focusing on data visualization and simple regression modeling. No advanced feature engineering or hyperparameter tuning is applied.
