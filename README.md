# 06.Election Exit Poll Prediction and U.S.A Presidential Speech Analysis using Machine Learning

This project is based on 2 case-studies: Vote Prediction and Text Analysis. The first project is to predict which party a citizen is going to vote for on the basis of their age and according to the answers given by the citizens to the questions asked in a survey conducted. The second project is based on the analysis of the inaugural U.S.A. Presidential speeches. One has to draw inferences based on the analysis done on these speeches.

## Skills and Tools

    - Text Mining Analytics
    - K Nearest Neighbour
    - Naive Bayes
    - Ensemble Techniques
    - Logistic Regression - Linear Discriminant Analysis

## Case study-1: Model Building
You are hired by one of the leading news channel CNBE who wants to analyze recent elections. This survey was conducted on 1525 voters with 9 variables. You have to build a model, to predict which party a voter will vote for on the basis of the given information, to create an exit poll that will help in predicting overall win and seats covered by a particular party.

Dataset for Problem: Election_Data.xlsx

    - Data Ingestion: 12 marks
    1. Read the dataset. Do the descriptive statistics and do null value condition check. Write an inference on it. (5 Marks)
    2. Perform Univariate and Bivariate Analysis. Do exploratory data analysis. Check for Outliers. (7 Marks)

    - Data Preparation: 5 marks
    1. Encode the data (having string values) for Modelling. Is Scaling necessary here or not? Data Split: Split the data into train and test (70:30). (5 Marks)

    - Modelling: 26 marks
    1. Apply Logistic Regression and LDA (linear discriminant analysis). (5 marks)
    2. Apply KNN Model and Naïve Bayes Model. Interpret the results. (7 marks)
    3. Model Tuning, Bagging (Random Forest should be applied for Bagging) and Boosting. (7 marks)
    4. Performance Metrics: Check the performance of Predictions on Train and Test sets using Accuracy, Confusion Matrix, Plot ROC curve and get ROC_AUC score for each model.
        -Final Model: Compare the models and write inference which model is best/optimized. (7 marks)

    -Inference: 5 marks
    1. Based on these predictions, what are the insights? (5 marks)
    
  ## Case study-2: Text Mining
  
  In this particular project, we are going to work on the inaugural corpora from the nltk in Python. We will be looking at the following speeches of the Presidents of the United States of America:

President Franklin D. Roosevelt in 1941
President John F. Kennedy in 1961
President Richard Nixon in 1973

    - Find the number of characters, words and sentences for the mentioned documents. – 3 Marks
        (Hint: use .words(), .raw(), .sent() for extracting counts)

    - Remove all the stopwords from all the three speeches. – 3 Marks
    - Which word occurs the most number of times in his inaugural address for each president? Mention the top three words. (after removing the stopwords) – 3 Marks
    - Plot the word cloud of each of the speeches of the variable. (after removing the stopwords) – 3 Marks
    
