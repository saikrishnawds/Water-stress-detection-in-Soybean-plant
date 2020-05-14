# Water-stress-detection-in-Soybean-plant
This repository contains the realization of a neural network architecture that correctly classifies images of soybean plant based on Leaf wilting observed due to difference in water stress. 

In this context, water stress means some combination of not enough soil moisture + hot, dry air, 
which leads to more water being lost from the leaves than can be replaced from the soil.

Our Project aims to develop a model that indicates drought tolerance or sensitivity in Soybean plants, by studying the leaf wilting and classifying the degree of leaf wilting into different categories based on the extent of wilting. We are using 5 classes (from 0 to 4) in total for implementing this model, with 0 being the image depicting the least wilting to 4 depicting the most wilting by the soybean leaves in the images.
The data we are using to architect this novel classification system consists of images of soybean crops captured at various times of the day, and a csv file containing the respective annotations for the images. The csv file contains the information in one-hot encoding format which serve as the annotations for the training data.
So, the machine learning model we are employing for prediction uses certain crafted features of Computer Vision, mainly focusing on the implementation of a classic Convolutional Neural Network (CNN).

The CNN model designed can be roughly split into 4 categories as follows:
a) Input Layer
b) 1st Set of stacking Layers
c) 2nd Set of Stacking Layers
d) Fully Connected Output Layer
