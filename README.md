# Face-Mask-Detection-using-Deep-Learning
Face mask detection refers to the process of using Deep learning techniques to automatically determine whether individuals in an image are wearing face masks. This technology has become particularly relevant during the COVID-19 pandemic to ensure compliance with public health guidelines.<br>
<br>
In this project, we will be working on the Face Mask detection problem.

The Dataset contains images of people wearing masks and people not wearing masks. 
The database contains 10,000 colored images in the training folder, 
800 images in the validation folder, 
and 992 images in the test folder.

Our task is to create a CNN model for identifying whether a person in the image is wearing a mask or not.

performing the following tasks:

1.Downloaded the database.
2.Created test, train, and validation directory variables
3.Created train and validation data generator with target size (128,128)
4.Trained a CNN model
5.Trained a model with VGG19 model
6.Used callbacks to save your model at every step
7.Training may take several hours, so used 3 epochs only
