# Sports-Image-Classification

## Overview
Using the Keras deep learning framework, I was able to train a convolutional neural network (CNN) to classify images into 100 different sports. Originally I tried to train two models from scratch, but fialed to reach an adequate validation score due to overfitting, lack of data, etc. Instead, I chose to pursue the transfer learning route and trained a model on the ResNetMobileV2 CNN, with data augmentation, and was able to achieve a test-accuracy score of approximately 78%.
