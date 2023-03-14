# Sparkify-Project

  As part of the Udacity Data Science program, students are required to complete a capstone project using Spark, a popular big data processing framework. One such project involves predicting churn for Sparkify, a simulated music streaming service that closely emulates real-world streaming services like Spotify.

The goal of this project is to develop a model that can accurately identify users who are likely to cancel their subscription to Sparkify, based on their interactions with the platform. This involves analyzing a large dataset of user activity logs, which includes information such as the songs played, the length of each session, and the type of device used.

## Motivation
The motivation to write this project is to gain experience in working with real-world datasets and to practice data cleaning, exploration, and visualization techniques. This project will provide an opportunity to apply various data analysis skills using Python and PySpark, which are valuable skills in the field of data science. Additionally, by completing this project, one can gain insights into user behavior and preferences, which can help businesses improve their services and make data-driven decisions.

## Installation

- Python 3.6
- PySpark ML
- Jupyter
## Results
  In our churn prediction model, we selected the Random Forest algorithm since it outperformed other models, including Decision Trees and Logistic Regression, consistently. Our final model delivered an accuracy of 0.74, precision of 0.7, and F1 Score of 0.7, demonstrating that our model accurately predicts churn users.

| Model Name         | F1-score |
| ------------------ | -------- |
| Random Forest      | 0.70     | 
| Decision Tree      | 0.69     |
| Logistic Regression| 0.63     | 

Please check my blog post to get more details, here is the [link](https://medium.com/@valygnos/how-data-science-can-help-music-streaming-services-retain-users-699e4ea8cfe8).

## References

Dataset provided by [Udacity](https://cn.udacity.com/).
