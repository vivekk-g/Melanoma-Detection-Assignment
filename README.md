# Melanoma Detection Assignment
> In this assignment, built a multiclass classification model using a custom convolutional neural network in TensorFlow.
> A CNN based model which can accurately detect melanoma from the scan images.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis. In this assignment, building multiclass classification model using a custom convolutional neural network in TensorFlow.
- The model can classify images in malignant and benign oncological diseases (Actinic keratosis, Basal cell carcinoma, Dermatofibroma, Melanoma, Nevus, Pigmented benign keratosis, Seborrheic keratosis, Squamous cell carcinoma, Vascular lesion) 
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


## Conclusions
- Image augmentation got rid of overfitting
- Rectifying the class imbalance got rid of underfitting
- Final model has training and validation accuracy on similar numbers around 62%.
- After 30 epochs, Training and Validation loss reduced on each epoch.


## Technologies Used
- Tensorflow
- Numpy 
- Pandas 
- Matplotlib 
- Scikit-learn
- Augmentor 
- PIL 

## Contact
Created by [@vivekk-g] - feel free to contact me!
