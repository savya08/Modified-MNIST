# Modified-MNIST

## Dataset
The `train` and `mnistTask` folders contain the two datasets used in this project. 

The images in the `train` are 1200 x 900 dimensional grayscale images belonging to 62 classes. These classes are digits 0-9, lower-case letters a-z, and 
upper-case letters A-Z. 

`mnistTask` contains 28 x 28 dimensional grayscale images belonging to 10 classes. This dataset is riddled with a lot of label noise, i.e., the images are 
mislabelled.

## Tasks
1. Use the `train` dataset to train a CNN. Use no other data source or pretrained networks, and explain your design choices during preprocessing, model building 
and training. Also, cite the sources you used to borrow techniques. A test set will be provided later to judge the performance of your classifier. Please save 
your model checkpoints.

2. Next, select only 0-9 training images from the `train` dataset, and use the pretrained network to train on MNIST dataset. How does this pretrained network perform 
in comparison to a randomly initialized network in terms of convergence time, final accuracy and other possible training quality metrics? Do a thorough analysis. 
Please save your model checkpoints.

3. Finally, take the `mnistTask` dataset. Train on this dataset and provide test accuracy on the MNIST 
test set, using the same test split from part 2. Train using scratch random initialization and using the pretrained network of part 1. Do the same analysis as 2 
and report what happens. Try and do qualitative analysis of what's different in this dataset. Please save your model checkpoints.

## Libraries, Framework and Environment
* Google Colab
* TensorFlow
* TensorFlow Dataset
* TensorFlow Addons
* NumPy
