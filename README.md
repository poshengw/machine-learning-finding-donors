# Machine Learning Engineer Nanodegree
# Supervised Learning
## Project: Finding donors from census income dataset 

### Problem Statement
1. Performed several supervised algorithms to accurately model individuals' income using data collected from the 1994 U.S. Census (https://archive.ics.uci.edu/ml/datasets/Census+Income). The goal is to construct a model that accurately predicts whether an individual makes more than $50,000.
2. Optimized the algorithm to best model the data.
3. Data preprocessing: no invalid or missing entries we must deal with, however, there are some qualities about certain features that must be adjusted. This preprocessing can help tremendously with the outcome and predictive power of nearly all learning algorithms. (Step 4,5,6 )
4. Transforming Skewed Continuous Features. For highly-skewed feature distributions, it is common practice to apply a logarithmic transformation on the data so that the very large and very small values do not negatively affect the performance of a learning algorithm. Algorithms can be sensitive to such distributions of values and can underperform if the range is not properly normalized. Using a logarithmic transformation significantly reduces the range of values caused by outliers. It changes the shape of feature’s distribution. 
5. Scaling on numerical features. Applying a scaling to the data does not change the shape of each feature's distribution. however, normalization ensures that each feature is treated equally when applying supervised learners.  Note that once scaling is applied, observing the data in its raw form will no longer have the same original meaning, as exampled below.
6. converting non-numeric features to numeric by one-hot encoding. It creates dummy variable for each possible category. 
7. Shuffle and Split Data
8. Use F-beta score as a metric that consider both precision and recall
9. DecisionTreeClassifier, LogisticRegression and AdaBoostClassifier
9. GridSearch
10. AdaboostClassifier feature importances for Feature Selection.

