# FaceRecognization

Dataset : An external Source

Model : Simense Custom Model , Inception and VGG16.

Modules : Opencv,Tensorflow and Keras.
Experiments Face Recognization:

    1.Problem viewd as Binary Classification Problem
    2.Face recognization using Triplets.

**1. Face Recognization using One-shot algirthm**

    1.Here the Dataset taken as a pair of matching and non Matching Images.
    2. Detecting and Extracting the Faces using the OpenCV 
    3. Training with the Custom Siemese network with the Datasets.
    4. Evalution "accuracy score"
    
    **Results**: Got an accuracy of 70%

**2. Face Recognization using Triplets**

    1. Created the Triplet Dataset.
    2. Detecting and Extracting the Faces using OpenCV of target shape of (96,96,3)
    3. Trainig with the VGG16 and Inception Pretrained Model with the intialization of the Imagenet weights.
    4. Evalution Triplet loss
