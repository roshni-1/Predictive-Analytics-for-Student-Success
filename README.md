

# Predictive Analytics for Student Success

## Overview

This project involves the development of a predictive analytics system to identify and support students at risk of academic challenges. The system includes collecting, processing, analyzing, and visualizing data to provide actionable insights for educators and administrators.

## Dataset

The project utilizes a dataset consisting of the following CSV files:

- `demographic_data.csv`
- `academic_data.csv`
- `enrollment_data.csv`
- `behavioral_data.csv`
- `feedback_data.csv`

### Data Overview

The dataset contains information such as demographic details, academic performance, enrollment data, behavioral indicators, and feedback scores.

- Demographic data includes student ID, age, gender, and grade level.
- Academic data includes grades in various subjects, standardized test scores, attendance rates, study time hours, and more.
- Enrollment data includes course enrollment, class schedule, and extracurricular participation.
- Behavioral data includes disciplinary incidents, interactions with peers, participation in events, and engagement in extracurricular activities.
- Feedback data includes scores from students, teachers, and parents.

## Exploratory Data Analysis (EDA)

The EDA phase involved a thorough analysis of the dataset, including visualizations and statistical summaries. Key visualizations include scatter plots, histograms, box plots, and radar charts.

### Examples of Visualizations

![Image 1](https://github.com/roshni-1/Predictive-Analytics-for-Student-Success/blob/main/Distribution%20of%20age.png)
![Image 2](https://github.com/roshni-1/Predictive-Analytics-for-Student-Success/blob/main/Grades%20boxplot.png)
![Image 3](https://github.com/roshni-1/Predictive-Analytics-for-Student-Success/blob/main/countplot%20for%20course%20enrollments.png)
![Image 4](https://github.com/roshni-1/Predictive-Analytics-for-Student-Success/blob/main/enrollmentby%20extracurricular%20participation.png)
![Image 5](https://github.com/roshni-1/Predictive-Analytics-for-Student-Success/blob/main/feedback%20score%20distribution.png)
![Image 6](https://github.com/roshni-1/Predictive-Analytics-for-Student-Success/blob/main/gender%20distribution%20pie%20chart.png)
![Image 7](https://github.com/roshni-1/Predictive-Analytics-for-Student-Success/blob/main/correlation%20heatmap.png)
![Image 8](https://github.com/roshni-1/Predictive-Analytics-for-Student-Success/blob/main/overall%20correlation.png)
 *The visualizations may differ in the notebook as the notebook uploaded is final modified with no errors

## Predictive Modeling

The predictive modeling phase involves training machine learning models to identify students at risk of academic challenges. The project uses a Gradient Boosting Classifier, optimized using GridSearchCV.

### Model Evaluation

The model was evaluated using metrics such as accuracy, confusion matrix, and classification report.

## Conclusion

This project aims to provide valuable insights into student success using predictive analytics. The combination of exploratory data analysis, machine learning, and visualizations allows for a comprehensive understanding of the dataset and model predictions.



