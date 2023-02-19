# Assignment 3- Sampling Techniques
## UCS654: Predictive Analytics using Statistics

### Submitted By: Pranjal Arora, 102003402, 3CO16

After necessary Exploratory Data Analysis, it was found that the [dataset](https://github.com/AnjulaMehto/Sampling_Assignment/blob/main/Creditcard_data.csv) provided is unbalanced. The "fraudulent class" is minority class and constitutes just 1.172% of the provided dataset. The "non-fraudulent class" hence constitutes 98.128% of the dataset.

The features "Time" and "Amount" are not principal components, hence they are scaled to remove outliers, using the RobustScaler which removes the median and scales the data according to the quantile range.

5 different samples of the dataset are made, and 5 different Classifier models are applied to each sample, and Accuracy of each model is observed. 

To adjust the class distribution, the Majority class is under-sampled using Random Under Sampling. The Minority class is over-sampled using SMOTE and EEN. 

### Samples Made:-
1. Sample1:- Random Under Sampling
2. Sample2:- SMOTE Over-Sampling
3. Sample3:- SMOTE EEN Sampling
4. Sample4:- Stratified Sampling
5. Sample5:- Systematic Sampling

### Classifier Models Used:-
1. Support Vector Classifier
2. Random Forest Classifier
3. Decision Tree Classifier
4. Logistic Regression
5. KNN Classifier

### Accuracy Scores:-
![Accuracy Score](https://github.com/pranjal-arora/sampling-techniques/blob/master/Scores_Screenshot.png?raw=true)

### Conclusions:-
Random Tree Classifier gives highest accuracy for SMOTE EEN Over-Sampling method.

