# Introduction

Let’s say you scroll through social media and find a really cute dog picture. A question 
pops up in your head: *What breed is this dog? So adorable.* Maybe this thought just passes through your head or maybe you linger on it for a while. *No, seriously, what is this dog breed?*

This project aims to answer this question by analyzing pictures of 10 different dog breeds and identifying the breed of the dog. 

The dataset that was chosen was the [Stanford Dogs Dataset](http://vision.stanford.edu/aditya86/ImageNetDogs/) from Kaggle. Approximately 1209 samples were chosen as the training data, 92 samples served as the validation set, and 99 samples were the test set.

# Dataset
The Stanford dogs dataset had a total of 20 different breeds with at least 140 images per breed. Due to the vast amount of data there was, only 10 breeds were chosen and 140 images were taken from each breed. The total number of images in this dataset was 1400.

The 10 breeds were the following:
- Maltese Dog
- Afghan Hound
- Scottish Deerhound
- Pomeranian
- Irish Wolfhound
- Bernese Mountain Dog
- Samoyed
- Shih-Tzu
- Great Pyrenees
- Leonberg

# Tools

Keras was used to create the neural network models and scikit-learn was used to create the SVM model.

