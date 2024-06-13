# Encryptix

Hello, This is Om Prakash Behera, doing an internship at Encryptix in the domain of machine learning. For the completion of the internship, I am required to make three out of five given projects. I have attached a PDF containing all the given tasks.

Here is my GitHub repository containing the three projects in separate folders, namely:
- Movie Genre Classification
- Spam SMS Detection
- Credit Card Fraud Detection

For the projects, I have used datasets that are in the following Google Drive Folder:
https://drive.google.com/drive/folders/1zykb_eSOtj3HQLJgtLcuvY8Y0-EpLpF8?usp=drive_link

**Also, additional information about the accuracy of the models:**

The accuracy of the models is printed through a classification report. One such example is as follows:

              precision    recall  f1-score   support

           0       1.00      1.00      1.00    553574
           1       0.01      0.00      0.00      2145
    accuracy                           1.00    555719

**Interpretation of the report:**

- Precision: The ratio of correctly predicted positive observations to the total predicted positives.
- Recall: The ratio of correctly predicted positive observations to all the observations in the actual class.
- F1-Score: The weighted average of Precision and Recall. The F1-Score ranges between 0 and 1 and is useful when you need a balance between Precision and Recall.
- Support: The number of actual occurrences of each class in the dataset. This indicates how many spam and ham messages are in the test set.
- Accuracy: The overall accuracy of the model.
- Macro Average: The unweighted mean of the Precision, Recall, and F1-Score. This treats all classes equally regardless of their support.
- Weighted Average: The average of the Precision, Recall, and F1-Score, weighted by the support of each class. This gives more importance to the classes with more samples.
