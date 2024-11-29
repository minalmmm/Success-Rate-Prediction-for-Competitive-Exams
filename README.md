# Student Exam Prediction Dataset

## Overview
This dataset contains information about students' performance based on their **practice test scores** and **attendance percentage**. The goal is to predict whether the student will **clear the competitive exam**.

## Dataset Description

- **StudentID**: Unique identifier for each student.
- **Name**: Name of the student.
- **PracticeTestScore**: Score of the student on the practice test (out of 100).
- **AttendancePercentage**: Percentage of the classes attended by the student.
- **ClearedExam**: Target variable indicating if the student cleared the exam.  
    - `1`: Cleared the exam  
    - `0`: Did not clear the exam

### Sample Records from the Dataset

| StudentID | Name            | PracticeTestScore | AttendancePercentage | ClearedExam |
|-----------|-----------------|-------------------|----------------------|-------------|
| 1         | Aarav Sharma     | 85                | 95                   | 1           |
| 2         | Priya Desai      | 78                | 88                   | 1           |
| 3         | Rahul Patel      | 65                | 75                   | 0           |
| 4         | Neha Gupta       | 92                | 98                   | 1           |
| 5         | Vijay Kumar      | 58                | 60                   | 0           |

## Models Used
Various machine learning models were used to predict whether a student will clear the exam based on their practice test scores and attendance. These models include:

1. **Logistic Regression**
2. **K-Nearest Neighbors (KNN)**
3. **Decision Tree**
4. **Random Forest**
5. **Support Vector Machine (SVM)**

## Performance Metrics

The accuracy of the models on the test set was as follows:

| Model                    | Accuracy |
|--------------------------|----------|
| Logistic Regression       | 94.47%   |
| K-Nearest Neighbors (KNN) | 99.50%   |
| Decision Tree             | 100%     |
| Random Forest             | 100%     |
| Support Vector Machine    | 94.47%   |

### Key Observations:
- **Decision Tree** and **Random Forest** models achieved perfect accuracy (100%).(overfitting)
- **KNN** also performed well with a high accuracy of **99.5%**.
- **Logistic Regression** and **SVM** achieved an accuracy of **94.47%**, suggesting room for improvement, especially for more complex relationships in the data.
