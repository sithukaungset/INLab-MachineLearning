# INLab-MachineLearning
INLab Machine Learning related Project

Next Steps for Gradient Descent
delta w (change in the weights)= -  n (learning rate) the gradient which is a vector operator on the cost funciton C or L for loss function.

Two things to play with
1. which direction (direction)
2. how far, how many steps (magnitude)

Convolutional Nerual Networks

Correlation in CNN
Feature Extractor ==> Classification
Features are extracted by doing correlation although it is called convolution.

Feature Extraction 
1. Feature Extraction is hierarchical from high to low frequencies;
2. Feature Extraction is based on the receptive field idea originating with the receptive fields in neuroscience - Hubel and Wiesel

Classification is done with dense neural network as we did before a few layers dense, weights, relu(rectified linear unit)

Feature Extraction => ReLU Step

Feature Extraction => Max Pooling Step - End of Creating of a New Feature Map

New feature map is obtained by the shift muliply add algorithm with in general three-dimensional mask that is receptive field.
ReLU that entire result and subsample it and thats called max pooling,

Classification
1. Flatten Final Stack of features into vector of Neurones
2. This vector is the input to 1 or dense vectors in a MLP network architecture.
3. Final Layer is a softmax layer to do classification.
