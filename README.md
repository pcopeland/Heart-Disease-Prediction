# Heart_Disease_Prediction

### 1.1 Problem Statement
Heart disease is the leading cause of death among men, women, and people of most racial and ethnic groups in the United States. Approximately one out of every four I deaths are attributed to heart disease per year, nearly 660, 000. 

For my project I chose to study how machine learning models can be used to predict the likelihood of heart disease based on a number of lifestyle factors. The ability to identify probable causal relationships between risk factors and negative outcomes could save tens of thousands of lives every year.

Heart disease is a catch-all phrase for a range of diseases, including vascular disease (such as coronary artery disease), heart rhythm problems (arrhythmias), and congenital disabilities (congenital heart defects), etc. There are many risk factors for heart disease, such as smoking, age, exercise habits, and prior illnesses and family history, to name a few. In this report, I will outline the factors that I used, and what models I implemented to predict whether or not an induvial is likely to have heart disease. 

### 1.2 Dataset
I began with two datasets but ultimately chose just one because they didn’t have any features in common, and the dataset I chose had many times more instances. Originally, the dataset came from the CDC as a 2020 annual CDC survey of 400k adults and to their health status. The set is quite large, containing 18 columns (9 Booleans, 5 strings and 4 decimals), and 319,795 rows.

### 1.3 Proposed Analytics Solution
My proposed solution was to test three separate classification models to determine how accurately I could predict the presence or absence of heart disease. I trained and tested three separate models; logistic regression, KNN, and naïve Bayes. My target variable was simply whether or not the respondent had been diagnosed with heart disease, “Yes” or “No” (1 or 0).

Almost all of my features were categorical, which provided some unique challenges when deciding how to preprocess the data for modeling. My initial goal was to create a model that would identify the target outcome with an accuracy of 0.95 while also keeping false negative under 0.05. These threshold selections were random and only used as a goal. 
