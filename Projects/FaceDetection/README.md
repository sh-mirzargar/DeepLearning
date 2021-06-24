# Face detection

## description

In this project, we will train a face detection model, that given a picture will
return pixel coordinates of face occurrences. the dataset is several small
images of faces and non-faces (background, small part of faces). The images
have resolution 48x48 pixels. We will train a binary classification model and
use it to detect faces on the entire images.

1. Train a convolutional neural network for binary classification: we will implement and train a convolutional neural network for binary
classification of image patches of faces/non-faces
2. Run your fully-convolutional model on full images: Since our model is fully-convolutional - and no layer needs a fixed size
input - we can feed it with bigger images and get a spatial map of face
scores for different image patches
3. Hyperparamter finetuining and improving the model
