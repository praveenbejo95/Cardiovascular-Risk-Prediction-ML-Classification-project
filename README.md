# Cardiovascular-risk-prediction-ML-classification-project


![image](https://user-images.githubusercontent.com/92503896/209540890-1b2f1cc0-8d1a-4660-b91d-7a40e5136cc3.png)


## **Introduction:**

Heart disease is one the major cause of moribity and mortality globally. A heart attack happens when the flow of oxygen-rich blood to a section of heart muscle suddenly becomes blocked and the heart can’t get oxygen. If blood flow isn’t restored quickly, the section of heart muscle begins to die.

Doctors and Scientists across the globe have started to look into Machine Learning Techniques to develop screening tools.

## **Problem Description :**

In this project, we shall be giving you a walk through on the development of a screening tool for predicting whether a patient has a 10-year risk of developing coronary heart disease (CHD) based on their present health conditions using different Machine Learning Techniques.

## **Features description**

Breakdown of Our Features:

Sex: male or female("M" or "F")

Age: Age of the patient;(Continuous - Although the recorded ages have been truncated to whole numbers, the concept of age is continuous) Behavioral

is_smoking: whether or not the patient is a current smoker ("YES" or "NO")

Cigs Per Day: the number of cigarettes that the person smoked on average in one day.(can be considered continuous as one can have any number of cigarettes, even half a cigarette.) Medical( history)

BP Meds: whether or not the patient was on blood pressure medication (Nominal)

Prevalent Stroke: whether or not the patient had previously had a stroke (Nominal)

Prevalent Hyp: whether or not the patient was hypertensive (Nominal)

Diabetes: whether or not the patient had diabetes (Nominal) Medical(current)

Tot Chol: total cholesterol level (Continuous)

Sys BP: systolic blood pressure (Continuous)

Dia BP: diastolic blood pressure (Continuous)

BMI: Body Mass Index (Continuous)

Heart Rate: heart rate (Continuous - In medical research, variables such as heart rate though in fact discrete, yet are considered continuous because of large number of possible values.)

Glucose: glucose level (Continuous)

Predict variable (desired target)

10-year risk of coronary heart disease CHD(binary: “1”, means “Yes”, “0” means “No”) -DV

## **Steps involved doing this project:-**

The first step in the exercise involved exploratory data analysis where we tried to dig
insights from the data in hand. It included univariate and multivariate analysis in which
we identified certain trends, relationships, correlation and found out the features that had
some impact on our dependent variable.

The second step was to clean the data and
perform modifications. We checked for missing values and outliers and removed
irrelevant features. We also do Feature Engineering and one hot encoding for the
categorical features. 

The third step was handled the imbalanced data using SMOTE
technique. 

The fourth step was to try various machine learning algorithms on our split
and standardized data. We tried different algorithms namely; Logistic regression,
Decision tree, Random Forest, K-Nearest Neighbour, XGBoost, Support Vector Machine.
We did hyperparameter tuning and evaluated the performance of each model using
various metrics.

The best performance was given by the XGBoost and Random Forest
model with accuracy 93% and 89%, and F1_score was 93% and 89%, Precision was
96% and 91%, and Recall was 90% and 87% respectively.

## **Models Used**


      Logistic Regression
      SVM
      Decision Tree
      Random Forest
      K nearest neigbour
      XGBoost
      
 
 
## **Conclusions:**

Among all the classifiers XGBoost and Random Forest is giving the best performance.

The most important features who had a major impact on the model predictions were;
Age, Heartrate, totchol, BMI, Education, avgBP, and Glucose. Men are more likely to
have heart disease compared to women. factor. Elderly age group people are more at
risk to CHD then young and middle age group people. Heart disease is a severe problem
and though with age the chances of getting heart related problem increases, a good
balance between your diet and physical exercise will reduce the risk factor and help to
live longer.


1.Number of people belonging to middle age group are highest whereas
number of people belonging to young age group are lowest

2. Male and female both are equally prone to CHD

3. Number of male smoker is higher than female smokers.

4. People who suffered previously from a heart attack have high chances
of getting CHD.

5. XGBoost performed the best among all other models with highest
accuracy and f1 score

6. heartrate is the most important feature in predicting the CHD followed
by totChol and glucose.

