# predicting-diabetes-with-neural-network
Apply multilayer perceptron(MLP) that predict whether the patient is at risk of diabetes 
the first hidden layer has 64 nodes with  input dimensions  are 8 because there are 8 features and 
the second hidden alyer has 32 nodes. Finaly, the last layer has one node as we dealing with binary classification with 
sigmoid activation function.
we implemented the MLP in Keras using sequential model and trained the model using training data with iteration 200 and Adam optimizer.
the model is capable of predicting the onset of diabetes with 72.7%  
