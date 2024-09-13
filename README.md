# Neural_ICP4

PRIYA VARDHAN REDDY TAMMA         ID:700764913


Neural Network Assignment ICP_6 Programs

Use Case Description: Predicting the diabetes disease

Programming elements: Keras Basics

In class programming:

Use the use case in the class: a. Add more Dense layers to the existing code and check how the accuracy changes.

Change the data source to Breast Cancer dataset * available in the source code folder and make required changes. Report accuracy of the model.

Normalize the data before feeding the data to the model and check how the normalization change your accuracy (code given below).

from sklearn.preprocessing import StandardScaler

sc = StandardScaler()

Breast Cancer dataset is designated to predict if a patient has Malignant (M) or Benign = B cancer

In class programming:

Use Image Classification on the hand written digits data set (mnist)

Plot the loss and accuracy for both training data and validation data using the history object in the source code.
Plot one of the images in the test data, and then do inferencing to check what is the prediction of the model on that single image.
We had used 2 hidden layers and Relu activation. Try to change the number of hidden layer and the activation to tanh or sigmoid and see what happens.
Run the same code without scaling the images and check the performance?
