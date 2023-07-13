# BreastCancer
This is a Deep Learning Project where a model is developed which predicts whether a patient has Breast Cancer or not
## Workflow
* Load the Dataset from sklearn
* Add the data to the dataframe using pandas
* Since this a deep learning project ,import tensorflow and keras
* keras is an api that will be used in developing neural network models
* Analyze the dataframe using numpy functions to get an overview on dataframe
* Now Train the model to make a predictive model with minimum loss and more accuracy
## Spliting the data
* We have target values 0 and 1
* 0 indicates presence of Malignant ,these are tumor cells which causes breast cancer
* 1 indicates presence of Bengin,these tumor cells will not cause cancer
* use train_test_split to divide the data between X_train,X_test,Y_train,Y_test where test_size=0.2
* Now using data preprocessing we try to standardize the data so that the column values lie between 0 and 1 so that accuracy can increase after training the model
## Building Neural Network Model
* Here import tensorflow and keras
* Neural network model has input,hidden,output layers
* number of input layers are nothing but number of columns of the dataframe except the target variable
* number of output layers are equal to number of different categories of target varaibles
* compile the model using a suitable optmizer,loss,metrics function
* fit the data into model using a suitable validation split and epochs
* loss is nothing but difference between predicted and true value
## Visualizing data
* draw plot between accuracy of training and validation accuracy
* draw plot between loss during training and validation
* Check the accuracy scores on test data and training data
## Develop a predictive system
* Use input data after standardizing,reshaping for prediction

