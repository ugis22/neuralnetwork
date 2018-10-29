# Understanding Neural Networks

Neural networks is one of the most powerful and widely used algorithms when it comes to deep learning. At first look, neural networks may seem a *black box*; an *input layer* gets the data into the *"hidden layers"* and after a magic trick we can see the information provided by the *output layer*. However, understanding what the hidden layers are doing is the key step to neural network implementation and optimization.

As a consequence, the goal of this project is to understand and build a neural network

## What is a Neural Network?

The neural networks that we are going to considered are strictly called artificial neural networks, and as the name suggests, are based on what science knows about the human brain's structure and function. 

Briefly, a neural network is defined as a computing system that consist of a number of simple but highly interconnected elements or nodes, called 'neurons', which are organized in layers which process information using dynamic state responses to external inputs. This algorithm is extremely useful, as we will explain later, in finding patterns that are too complex for being manually extracted and taught to recognize to the machine. In the context of this structure, patterns are introduced to the neural network by the input layer that has one neuron for each component present in the input data and is communicated to one or more hidden layers present in the network; called 'hidden' only due to the fact that they do not constitute the input or output layer. It is in the hidden layers where all the processing actually happens through a system of connections characterized by weights and biases (commonly referred as W and b): the input is received, the neuron calculate a weighted sum adding also the bias and according to the result and a pre-set activation function (most common one is sigmoid, σ), it decides whether it should be 'fired' or activated. Afterwards, the neuron transmit the information downstream to other connected neurons in a process called 'forward pass'. At the end of this process, the last hidden layer is linked to the output layer which has one neuron for each possible desired output.

## What does this repository contain?

In this repository, there are two jupyter notebooks explained below:

* `Simple neural network.ipynb` explained how to create a simple neural network using a made-up input, a two layers containing sigmoid neurons and synapsis matrix, calculating the error to update weights.

* `Neural network.ipynb`
