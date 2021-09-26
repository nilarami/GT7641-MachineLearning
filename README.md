# GT7641-MachineLearning

To Run: 
Just run the python notebook labeled as SupervisedLearningProject.pynb in order to replicate all the results. I have attached the datasets, you will need to configure the location when reading from the csv files. 

Breast Cancer Dataset

You can access dataset here: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29 

This breast cancer dataset was obtained from the University of Wisconsin Hospitals, Madison from Dr. William H. Wolberg. The dataset is used to predict whether a user has breast cancer or not. There are 699 instances in the dataset. Dataset contains 16 missing values and the class distribution of the set is of the following: Benign: 458 (65.5%), Malignant: 241 (34.5%)  I removed the Sample Code Number from the training set since it’s a unique identifier and serves no purpose in terms of classification. 


Attribute
Domain
Sample Code Number
ID Number
Clump Thickness
1-10
Uniformity of Cell Size
1-10
Uniformity of Cell Shape
1-10
Marginal Adhesion
1-10
Single Epithelial Cell Size
1-10
Bare Nuclei
1-10
Brand Chromatin
1-10
Normal Nucleoli  
1-10
 Mitoses 
1-10
Class
0 - Benign, 1 - Malignant



Diabetes Dataset

You can access dataset source here: https://raw.githubusercontent.com/jbrownlee/Datasets/master/pima-indians-diabetes.csv 

The Pima Indians Diabetes Dataset involves predicting the onset of diabetes within 5 years in Pima Indians given medical details. This is also a 2-class classification problem. The number of observations for each class is not balanced. There are 768 observations with 8 input variables and 1 output variable. Missing values are believed to be encoded with zero values. 


Attributes
Number of Times Pregnant
Plasma Glucose Concentration a 2 hours in a oral glucose tolerance test
Diastolic Blood Pressure (mm Hg)
Triceps Skinfold Thickness (mm) 
2- Hour Serum Insulin (mu U/ml)
Body Mass Index (weight in kg/height in m^2) 
Diabetes Pedigree Function
Age(years)
Class Variable(0, 1)




