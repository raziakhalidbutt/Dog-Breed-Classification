# Dog Breeds Classification using CNN with Transfer Learning

# Table of content
1. [Installation](#Installation)
2. [Motivation](#Motivation)
3. [Steps](#Steps)
4. [Data](#Data)
5. [File Description](#FileDescription)
6. [Results](#Results)


<a name="Installation"></a>
# Installation

You need Anaconda distribution of python 3.* version. Additional libraries required are:

* Keras
* OpenCV
* Matplotlib
* Numpy

<a name="Motivation"></a>
# Motivation

This project is part of Data Scientist Nanodegree Program from Udacity. The goal is to classify images of dogs according to their breed. If a dog is detected in the image, it will provide an estimate of the dog's breed. If a human is detected, it will provide an estimate of the dog breed that is most resembling.

<a name="Steps"></a>
# Steps

Following are the steps perform in dog_app.ipynb notebook.

    Step 0: Import Datasets
    Step 1: Detect Humans
    Step 2: Detect Dog
    Step 3: Create a CNN to Classify Dog Breeds (from Scratch)
    Step 4: Create a CNN to Classify Dog Breeds (using Transfer Learning)
    Step 5: Write Your Algorithm
    Step 6: Test Your Algorithm
    
<a name="Data"></a>
# Data
The data for this project is located [here](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).

<a name="FileDescription"></a>
# File Desciption

* **dog_app.ipynb:** Jupyter notebook containing the algorithm and process used to create it.
* **Haarcascades folder:** Xml file use with the OpenCv face detector class.
* **saved_models folder:** models that attains the best validation loss.
* **test-images folder:** Images in jpg format used to test the algorithm's predictions.


<a name="Results"></a>
# Results

* Accuracy achieved by this model is 79.9% 
* For German shepherd image the model identify it breed correctly. But for husky model not able to differentiate it from Alaskan malamute. 
* For detected human with clear face it able to classify their most resemble dog breed. 
* Model need much improvement so that it can also differentiate between very similar dog breeds and can also detect multiple dogs in images. 
* There is also need to increase more training data and the breed categories.  We also need to fine-tune hyperparameters. 

You can find more in my [blog]().

