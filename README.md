# lending_club_loan_default_classification_part_1
The project is split into 3 parts. This notebook is the [Part 1 - Data Exploratory Analysis on Lending Club Loan Data](https://yzclaire.github.io/lending_club_loan_default_classification_part_1/)


### Data

The dataset for this project is available on Kaggle.com and also provided by the official website of Lending Club. It has more than 2.2M rows of loan entries and 150 column of features

[Link to Data](https://www.kaggle.com/wordsforthewise/lending-club)


### Project Outlines:

#### 1. Define goal 

    a.Identify most important attributes separating bad loans and good loans 
    b.Build Xgboost model to make prediction
    
#### 2. EDA

    a.Data first impression
      -available predicting variables
      -data distribution
      -missing values
    b.Split dataset in to training and test set
    c.correlation analysis and remove multicollinearity
    d.Data Visualization to explore relationship between target and predicting variables
    
#### 3. Data Cleansing and Feature Engineering

    a. Handling missing values
    b. Transform any characteristics or categorical variables into numeric
    c. Create new features from existing features

#### 4. Prepare dataset for modeling:
    - Standard scale
    - Handling Dataset imbalance issues (upsampling)
        
#### 5. Model Training and Evaluation
    1). Logistic regression with L1 regularization model
    2). Random Forest model 
    3). Xgboost model
        -hyperparameters Tuning
    
#### 6. Feature Selections Consideration
    - Remove variables according to correlation analysis
    - Logistic regression with L1 regularization (coeffecients not zero)
    - Random Forest model built-in feature importance

#### 7. Assess any additional feature engineering or feature selection opportunity based on model results

#### 8. Choose the best model and evaluate prediction on test dataset

#### 9. Areas of improvements

 
