# -Breast-Cancer-Diagnosis
Breast Cancer Diagnosis Using k-Nearest Neighbors

Abstract: Breast cancer is the most common invasive cancer in women, and the second main cause of cancer death in women, after lung cancer. Early  can increase the chance of finding breast cancer before it spreads. We can predict whether the tumor is malignant or benign by using ‘Machine Learning’. To do so, we can use k-Nearest Neighbors model. This paper contains the necessary steps to implement k-Nearest Neighbors model that is actually predicting whether the tumor is malignant or benign. 

Introduction  
This is an implementation of k-Nearest Neighbors model in python to diagnosis breast Cancer classification. The implementation allows users to get to know whether it is in malignant or benign stage.  

If you have been diagnosed with a tumor, the first step your doctor will take is to find out whether it is malignant or benign, as this will affect your treatment plan. In short, the meaning of malignant is cancerous and the meaning of benign is non-cancerous.  

Necessary Steps to implement:  

Importing library:  
The first step is to import the necessary libraries so that we can use specific function of those libraries. 

Importing the data dataset: 
To predict breast cancer some relevant dataset needs to be imported.

Preprocessing:  
The next step is to split the dataset into its attributes and labels.

Train Test Split: 
Training and testing on the same data is not an optimal approach, so we do split the data into two pieces, training set and testing set. We use ‘train_test_split’ function to split the data. Optional parameter ‘test-size’ determines the split percentage. 

feature scaling:  
Before making any actual predictions, it is always a good practice to scale the features so that all of them can be uniformly evaluated.

Training and prediction:
It is extremely straight forward to train the KNN algorithm and make predictions with it, especially when using Scikit-Learn. 
‘KNeighborsClassifier’ is to be imported first class from the ‘sklearn.neighbors’ library. In the second step this class is initialized with one parameter that is nothing but the value for the K. Here, we have taken k=5. The final step is to make predictions on our test data.

Evaluating the Algorithm:  
For evaluating an algorithm, confusion matrix, precision, recall and f1 score are the most commonly used metrics. The confusion_matrix and classification_report methods of the sklearn.metrics can be used to calculate these metrics.

CONCLUSIONS:
Breast cancer can’t be prevented.  But early detection can increase the chance of finding breast cancer before it spreads and life can be saved.  This model can predict whether tumor is malignant or benign with great accuracy that can be helpful for the doctor to take quick decision.
