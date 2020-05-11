# Artificial Neural Networks
ANNs are the basics for Deep Learning. The reporsitory contains many examples. We would first look into why Deep Learning is preferred by comparing different types of problems. Later we will also see examples of ANN Models on MNIST Data and Fashion Images dataset. Stock Price prediction can also be done with ANN, we will examine this and we would also get some relavant data from internet and check if that helps our case.

## Implementation:
Basic implementation with detailed steps are [Here](https://nbviewer.jupyter.org/github/saianil58/Artificial-Neural-Networks/blob/master/Multiclass%20Classification/Multi_Class_classification.ipynb) and this notebook is using IRIS dataset which is a Multi Class classification.

## Case Studies:
### Regression Model:
Boston Housing Prices Dataset is a base for Regression problems, [here](https://nbviewer.jupyter.org/github/saianil58/Artificial-Neural-Networks/blob/38b4580ec86736e06a7e660d6fe1906940ad4eb6/Regression/Regression_Keras.ipynb) is a notebook which has implementations of a basic ANN and using that we have the MAE of 20 on Testing data, which is better than any basic model.

### Binary Classification:
HR Analytics dataset, to predict the employees who will stay in orgnization. [Here](https://nbviewer.jupyter.org/github/saianil58/Artificial-Neural-Networks/blob/47df6bd2dcec91460a9062191ebaf0852670ae15/Binary%20Classification/binary_classification_keras.ipynb) is the notebook with details of the implementation. A simple Logistic Regression model gave 75% of accuracy and ANN model gave 95% both wihtout any Tuning. ANN performs better than Logistic Regression Model.

## Identify the Digits:

## Identify the apparels:
This is similar to MSIST data, however the images are of apparels. In [this](https://github.com/saianil58/Artificial-Neural-Networks/blob/master/Image%20Classifications/Fashion_images.ipynb) notebook we would build an ANN model and then check various modifications we can do to the model to improve the prediction capabilities. There are graphs which would support the arguments while we work on improving the Accuracy.

## Hyperparameter Tuning with TALOS:
A machine learning model has two types of parameters:

trainable parameters, which are learned by the algorithm during training. For instance, the weights of a neural network are trainable parameters.

hyperparameters, which need to be set before launching the learning process. The learning rate or the number of units in a dense layer are hyperparameters.

Hyperparameters can be numerous even for small models. Tuning them can be a real brain teaser but worth the challenge: a good hyperparameter combination can highly improve your model's performance. Here we'll see that on a simple CNN model, it can help you gain 10% accuracy on the test set!

Thankfully, open-source libraries are available to automatically perform this step for you!

One such library is TALOS.[Here](https://nbviewer.jupyter.org/github/saianil58/Artificial-Neural-Networks/blob/c1876138e8a0be947bf1b2e5fa2c9765c5423a5f/Binary%20Classification/Bank%20Churn%20Prediction%20using%20ANN.ipynb) is a notebook which will give details on how to use TALOS pacakge for tuning of Keras models.
