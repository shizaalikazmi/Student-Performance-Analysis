# **Student-Performance-Analysis**

A data analysis project that investigates academic performance patterns across Math, English, and Science scores — exploring the influence of gender, score distributions, and overall final percentage categories using Python.

📌 **Overview**

This project performs exploratory data analysis (EDA) on a Student Performance Dataset sourced from Kaggle. It applies data filtering, grouping, binning, and multi-chart visualization to extract meaningful insights about student achievement across subjects and demographic groups.

🔍 **Key Findings**

Students scoring above 90 in English are identified and counted as a high-performing group

Female students have a measurable average Science score, computed separately for gender-based comparison

Students are categorized into performance tiers (Low, Average, Good, Excellent) based on Final Percentage, and average Math scores are compared across these tiers

Math and English scores show a visible relationship when plotted against each other

Science score averages differ by gender, visualized through a grouped bar chart

A filtered export of students scoring above 95 in Science is saved for downstream use

🛠️ **Tech Stack**

Python --> Core programming language
Pandas --> Data loading, filtering, grouping, and binning
NumPy --> Numerical operations
Matplotlib --> Histograms, scatter plots, bar charts, boxplots, and heatmap
Seaborn --> Styling and supplementary visualization

📊 **Visualizations Included**

Histogram — Distribution of English scores across all students

Scatter Plot — Relationship between Math and English scores]

Bar Chart — Average Science score grouped by gender

Boxplot — Outlier detection and spread of Math scores

Correlation Heatmap — Correlation across all numeric features in the dataset

🗂️ **Project Structure**

student-performance-dataset-analysis/

├── project2.ipynb                  # Main Jupyter Notebook

├── Student_Performance_Dataset.csv # Raw dataset (input)

└── high_writing_students.csv       # Filtered output (Science score > 95)

📁 **Dataset**

Source: Kaggle — Student Performance Dataset

Features: Gender, Math Score, English Score, Science Score, Final Percentage

