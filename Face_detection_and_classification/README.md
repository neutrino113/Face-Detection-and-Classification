# Face_detection_and_classification
This repository consists of a Machine Learning based model that is used to classify human face 

## About Data Collection
In this project we try to collect real time images from user Webcam Video stream <br>
In the image frame we will extract all the faces detected in it using Harcascade classifier <br>
And we will store the faces extracted from the webcam in the data folder as as a numpy array

## About Data Preperation
We collect the face data in a numpy array and for each face we create a label, and then conacatenate these labels 
with the face data and store in numpy appay

## About our Classifier Model
* Load the traning data from the data folder contaning numpy arrays of all persons
* Read a video stream using openCV
* Extract faces out of it
* use KNN to classify the face
* Map the predicted id to the name of the user
* Display the predictions on the screen
