# AIML-TASK2-EDA
# AIML-Task2-EDAAdd commentMore actions
# AIML-Task2-EDA
#  Titanic Dataset - Exploratory Data Analysis (EDA)

This project performs *data cleaning, **exploratory data analysis (EDA), and **visualizations* on the Titanic dataset to understand factors affecting passenger survival.
 📌 Objective

The goal is to analyze the Titanic dataset to:

- Clean and preprocess the data.
- Explore statistical summaries and feature relationships.
- Visualize patterns using histograms, boxplots, and correlation heatmaps.
- Draw insights from feature-level visual analysis.
📁 Dataset
- Dataset used: [Titanic - Machine Learning from Disaster](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- File name: Titanic-Dataset.csv  
- Contains data for *891 passengers*, with features such as:
  - Survived (target), Pclass, Sex, Age, Fare, Embarked, etc.
 🛠️ Tools & Libraries

- Python
- Jupyter Notebook
- Libraries:
  - Pandas, NumPy
  - Matplotlib, Seaborn
  - scikit-learn

✅ Key Steps

1. Data Cleaning
- Handled missing values in Age (median) and Embarked (mode).
- Dropped Cabin column due to high percentage of missing values.
- Encoded categorical features like Sex.
- Standardized Age and Fare.

2. EDA and Visualizations
- Generated summary statistics (mean, median, std).
- Created histograms and boxplots for numeric features.
- Visualized correlations using a heatmap.
- Analyzed survival rates by Sex, Pclass, and other features.

3. Inferences
- Females and 1st class passengers had higher survival rates.
- Higher fares were associated with better survival chances.
- Younger passengers and children had slightly better survival rates.
- Strong correlation observed between Fare, Pclass, and Survived.
