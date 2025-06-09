
# **Coupon Acceptance Prediction**

This project uses machine learning to predict whether a person will accept a coupon based on various contextual and demographic features such as destination, time of day, passenger type, income level, and more. The dataset was originally collected through a survey on Amazon Mechanical Turk and is featured in the research paper.


**Dataset source**: UCI Machine Learning Repository

**Dataset link**: https://archive.ics.uci.edu/dataset/603/in+vehicle+coupon+recommendation

## Dataset Overview

The dataset contains information about different driving scenarios and the decision of whether or not the driver accepts a coupon. Features include:

- Demographics: age, gender, education, marital status, income, etc.

- Contextual Information: weather, time, destination, temperature.

- Behavioral Features: frequency of visits to bars, coffeehouses, restaurants.

- Coupon Information: type of coupon, expiration duration.

- Geographic and Directional Info: driving time to coupon   location, whether the location is on the same route.

## Project Objective
To build and compare various classification models that can predict whether an individual will accept a coupon in a given situation.

## Tools & Libraries Used

- **Python**

- **Pandas, NumPy** – Data preprocessing and exploration

- **Matplotlib, Seaborn** – Visualization

- **Scikit-learn** – Model training, evaluation

- **LabelEncoder, OneHotEncoder** – Encoding categorical features

- **Chi-Square Test** – Feature selection

## Models Used
- K-Nearest Neighbors
- Support Vector Classifier (SVC)
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier

## Data Preprocessing
- Handled missing values using appropriate imputation strategies.

- Combined time-related and distance-related features for   simplification.

- Encoded nominal features using OneHotEncoding.

- Encoded ordinal features using LabelEncoding.

- Scaled numerical features where necessary.

- Applied Chi-Squared test for feature selection.

## Model Evaluation
Models were evaluated based on:
- Accuracy
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

##  Best Performing Model
After comparing multiple algorithms, the Random Forest Classifier provided the best balance of performance and interpretability, with an accuracy of ~74.
