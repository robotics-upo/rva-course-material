# Deep Learning Basics
In this case, we will learn how to implement and train a simple CNN for image classification, and to use a trained network within our OpenCV code

We will be using Google Colab:

https://colab.research.google.com

https://medium.com/tensorflow/colab-an-easy-way-to-learn-and-use-tensorflow-d74d1686e309

Google Colab offers an environment with a Jupyter notebook preinstalled, as well as TensorFlow.

https://jupyter.org

The videos explaining the execution of the different notebooks can be accessed through the online classroom system https://aulavirtual.upo.es

# Homework 1

Execute the notebook learning-imageclassification.iypnb

Modify the network (changing the architecture) and training parameters to achieve at least an accuracy of 75% in the test set. 

Consider longer periods for training and additional layers. Include dropout layers to reduce overfitting (https://keras.io/api/layers/regularization_layers/dropout/)



# Homework 2

Execute and understand the notebook deploying-imageclassification.iypnb

Improve the module to detect as many cars as possible in the image test.jpg. 

You can modify the network, for instance, to focus only on car detections (change the training setup and the output to consider only two classes: cars and others). Also, modify the procedure to use the network for car detection sweeping it through the original image at different scales. 

