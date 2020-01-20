# cifar10-cnn
Experiment with convolutional neural networks and fully connected neural networks on cifar10 dataset, using Keras

- Compare the accuracy of the convolutional neural network on the cifar10 dataset to the accuracy of dense neural networks with 0, 1, 2, 3 and 4 hidden layers of 512 rectified linear units each (with a dropout rate of 0.5).

- Compare the accuracy of the convolutional neural network with a modified version that replaces each stack of (CONV2D, Activation, CONV2D, Activation) layers with 3x3 filters by a smaller stack of (CONV2D, Activation) layers with 5x5 filters. 
