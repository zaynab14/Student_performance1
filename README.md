# Student Performance Prediction using Logistic Regression



## Project Overview



This project was completed as part of the \*\*HisabDo AI/ML Internship – Day 4 Task\*\*.



The objective is to build a Machine Learning classification model that predicts whether a student will \*\*Pass\*\* or \*\*Fail\*\* based on their academic performance and attendance.



---



## Dataset



The dataset contains student academic records with the following features:



- Student Name

- Age

- Gender

- Course

- Attendance

- Assignment Score

- Midterm Score

- Final Score



A new target column was created:



- \*\*Pass = 1\*\*

- \*\*Fail = 0\*\*



---



## Technologies Used



- Python

- Pandas

- Matplotlib

- Scikit-learn

- Google Colab



---



## Data Preprocessing



The following preprocessing steps were performed:



- Loaded the dataset using Pandas

- Checked dataset information

- Handled missing values

- Removed duplicate records

- Corrected invalid attendance values

- Created the target variable (Pass/Fail)



---



## Features Used



The following features were used to train the model:



- Attendance

- Assignment Score

- Midterm Score

- Final Score



---



## Machine Learning Model



The classification model used in this project is:



**Logistic Regression**



The dataset was divided into:



- 80% Training Data

- 20% Testing Data



---


## Model Evaluation



The model was evaluated using:



- Accuracy Score

- Confusion Matrix

- Classification Report



### Model Accuracy



*\*Accuracy: 83.33%\*\*



---



## Visualizations



The project includes the following visualizations:



- Pass vs Fail Distribution

- Confusion Matrix



---



## Project Structure



```

Student-Performance-Prediction/

│

├── student\_performance.csv

├── Student\_Performance\_Prediction.ipynb

├── README.md

└── charts/

&#x20;   ├── pass\_fail\_distribution.png

&#x20;   └── confusion\_matrix.png

```



---



## What I Learned



Through this project, I learned how to:



- Load and preprocess datasets using Pandas.

- Create a target variable for classification.

- Split data into training and testing sets.

- Train a Logistic Regression model using Scikit-learn.

- Make predictions on unseen data.

- Evaluate model performance using Accuracy, Confusion Matrix, and Classification Report.

- Visualize model results using Matplotlib.



---



## Conclusion



The Logistic Regression model successfully predicted whether students would pass or fail based on their attendance and academic scores. The model achieved an accuracy of \*\*83.33%\*\*, demonstrating the complete workflow of a basic Machine Learning classification problem.

