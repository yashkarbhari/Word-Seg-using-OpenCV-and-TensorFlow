# Word-Segmentation-using-opencv-and-tensorflow

This is a dataset from Kaggle where the goal was to segment the captcha images with each character. Here we use the OpenCV library to 
You can find the dataset [here](https://www.kaggle.com/fournierp/captcha-version-2-images)

![](Captcha%20Image.png)

The images are 5 letter words that can contain numbers. This dataset is a perfect opportunity to attempt to make __Optical Character Recognition__ algorithms.

Here, I have applied to approaches,
1) Using OpenCV and creating bounding box for the image using hard-coded dimensions for the bounding boxes as the reCAPTCHA images in the dataset since, the letters are at the same place for every image.

2) Using TensorFlow I trained the model using Convolutional, MaxPooling, and BatchNormalization layers and tested the model on the test dataset with test accuracy of __93%__.  
