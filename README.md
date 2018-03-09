# Keras-learning

## [Deep Learning: Keras Short Tutorial](https://www.youtube.com/watch?v=Tp3SaRbql4k)

### What is Kers?

- Neural Network Library written in Python\n

- Designed to be straightforward yet extensive

- Build on top of either Theano as newly TensorFlow

#### Why use Keras

1 simple to start and going

* Written in python, easy to expand
* Deep enougth to build serious models

### General Design
General Idea is to beased on layers and input/output
- Prepare your inputs and ouput tensors
- Create first Layer to handle input tensor
- Create output layer to handle targets
- Build Virtually any model you like in between


![](Keras-learning/Capture.PNG)

### Layers and Layers
Keras has pre built layers.
- Regular dense, MLP type
Create a layers:
keras.layers.core.Dernse(output_dim.
  init
  activation
  weights
  ...)
  
- Recurrent layers, LSTM,GRU, etc
- 1D Convolutional layers
- 2D Convolutional layers

### Autoencoders can build with any other type of layer

