# Heart Disease Classification
### Predicting whether a person has Heart Disease or not using Machine Learning
### We are going to cover the following approach
### 1. Problem Definition
### 2. Data
### 3. Evaluation
### 4. Features
### 5. Modelling

## 1. Problem Definition
In a nutshell

Given Clinical parameters of the patient can we predict whether a person has Heart Disease or not?

## 2. Data
### Source (taken from UCI) : https://archive.ics.uci.edu/ml/datasets/heart+Disease

1. age
2. sex
3. cp
4. trestbps
5. chol
6. fbs
7. restecg
8. thalach
9. exang
10. oldpeak
11. slope
12. ca
13. thal
14. target (the predicted attribute)

## 3. Evaluation :
What defines Success?

If we achieve 95% accuracy in predicting whether a person has Heart Disease or not, only then will the project be persuaded

## 4. Features¶
#### Details about the Data
#### Data Dictionary :
1. age: age in years
2. sex: sex (1 = male; 0 = female)
3. cp: chest pain type
   * Value 1: typical angina
   * Value 2: atypical angina
   * Value 3: non-anginal pain
   * Value 4: asymptomatic
4. trestbps: resting blood pressure (in mm Hg on admission to the hospital)
5. chol: serum cholestoral in mg/dl
6. fbs: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
7. restecg: resting electrocardiographic results
   * Value 0: normal
   * Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
   * Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
8. thalach: maximum heart rate achieved
9. exang: exercise induced angina (1 = yes; 0 = no)
10. oldpeak = ST depression induced by exercise relative to rest
11. slope: the slope of the peak exercise ST segment
   * Value 1: upsloping
   * Value 2: flat
   * Value 3: downsloping
12. ca: number of major vessels (0-3) colored by flourosopy
13. thal: 3 = normal; 6 = fixed defect; 7 = reversable defect
14. target: 0-Not Heart Disease, 1-Heart Disease

## 5. Modelling 
Different Modelling Techniques for classification like K-Nearest Neighbors, Random Forest Classifier and Logistic Regression will be used
