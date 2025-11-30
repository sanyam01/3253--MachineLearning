**Link to github:**  
[https://github.com/saeid-uot/3253-Machine-Learning](https://github.com/saeid-uot/3253-Machine-Learning)

**Sept 14, 2025**

1. Supervised learning \- 2 types Regression (when labels are continuous) and Classification (discrete labels)  
2. Unsupervised learning \-\> clustering algorithm  
3. Naming convention \-\> features are denoted by x and labels are denoted by y.   
4. If x is small, it’s one feature. If it's X it’s multiple features.  
5. Linear Regression and Non-Linear regression  
6. Decision boundaries in classification learning, that decided what is what.  
7. Clustering is unsupervised learning  
8. Batch Learning \- You have batches of data to train  
9. Online learning \- Where you don’t have enough data but you train the model as you get more data. E.g. covid 19  
10.   Instance  based learning vs model based  learning  
11. Instance based learning \-\> where system learns the examples by heart, then generalizes to new new cases using similarity measure  
12. K-nearest neighbor is an example of instance learning. This is an algorithm basically.  
    We measure Euclidean distance  
    How do we choose K:  
    K cannot be 1, k cannot be equal to total neighbors. Only instance based is k-neighbors. Rest all are model based that we will learn.  
13. Model based learning  
    You give all the data to the model and the model decides the decision boundaries.  
14. Deterministic Model or Statistical Models \- Answer will always be correct  
15.  During modelling, we are trying to make relationships between features and labels.  
16. Probabilistic Models : There are chances of error  
17. Loss Functions:  
    Root Mean Square Error and Mean Absolute Error → 2 loss functions for supervised learning  
18. Feature Scaling → Normalization or min-max scaling. All the data will be between 0 \` and 1  
    Another technique is Standardization  
19. Min-max makes the values between 0 and 1  
20. Standardization depends on the features.  
21. For neural nets, it's better to use min-max scaling  
22. Problem with min-max is if one of the values is very large or very small (so basically if its outliers)  
23. Typically 20% of dataset is considered as testing dataset  
24. Stratification for testing dataset  
25. Training, Validation, and Testing (60, 20, 20\)  
26. Classification of the data is very important  
27. Visualize your data as much as you can  
28. Correlation : Values are between \-1 to 1\. It is the measure of degree to which 2 variables have a relationship between them.  
29. Positive correlation means value increases with other variable changing and vice versa  
30. Correlation is helpful in keeping the features that have relationship with the labels

**Sept 18, 2025**

31. Encoding Features

1. One-Hot-Encoding

Replacing category with dummy variables

32\. Learn what is underfitting and what is overfitting  
33\. Optimal values of hyper parameters are essential for the performance of the models  
34\. 

**Sept 25 \- Classification Models**

Binary Classification : When there  are only 2 type of labels/classifiers  
We use classification models for marketing a lot.

1. Use Kaggle  
2. Use Toronto Police data  
3. Statcan  
4. Ontario  
5. Or you can start blending multiple datasets  
6. Sensitivity and Specificity, Accuracy

	Sensitivity \= True positive/positive or True Positive/(True Positive \+ False Negative)  
	Above 3 parameters should only be used if there is balanced dataset

7. Imbalanced Dataset  
8. Precision and Recall \-\> They work on balanced and unbalanced dataset  
   Precision is TP/TP+FP  
   Recall TP/TP+FN  
   These are used properly and help in models  
9. In ML, when we are doing predictions we are often looking at a positive class. Ideally, we want a very high recall. Because we are looking at cases that are actually positive. And we are looking at normally minority classes because that is practically true in real-life cases.  
10. F1 is called harmonic mean/ average of precision and recall. Why is it needed, because let's say if precision is 99% and recall is 54%. We do harmonic mean not average because harmonic mean goes more towards lower value rather than giving average.  
11. ROC Curve

Above all concepts for today was binary classification

**Points to look for data**

1. Credit card fraud  
2. 