# abalone neural network
  
Predicting abalone's life expectancy using neural network architecture.  
Features:  
* Multi-layer Perceptron
* Abalone dataset
* Estimate abalone life
  
The dataset used in this project was obtained from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/abalone).

## Introduction
### Abalone
Abalone are type of shellfish that are common along the coasts of most continents across the world. By cutting through the shell of an abalone, its age can be determined by counting the number of rings using a microscope. It's burdensome process so we try to do this using  a number of explanatory factors, like height or weight.  
  
### Multi-layer Perceptron
Multi-layer Perceptron is a popular type of artifical neural network. A MLP consists of, at least, three layers of nodes: an input layer, a hidden layer and an output layer. Hidden layers could be much more. Input layer receive the signal, and output layer makes a decision or prediction about the input.Perceptrons are trained by successively updating the weights until the outputs of the perceptron closely match the “ground truth” (known outputs).  

This may be represented by the following diagram:

![mlp](../master/res/mlp.png)

## Results

![results](../master/res/results.png)  

As you can see, implemented artifical neural network predicts abalone's rings with MAE(Mean Absolute Error) equal to 1.470, which is a good approximation actual number of rings.  
  
Architecture of our MLP:  
* two hidden layers [20,5]
* activation function: logistic
* regularization parameter: 0.001
* learning rate: 0.001

## Prerequisites
### Tools
* jupyter notebook 
After you have installed the jupyter notebook on your computer, you are ready to run the notebook server.You can start the notebook server from the command line by running:  
```
jupyter notebook abalone-network.ipynb
```
### Lbraries
You need to have installed and configured following libraries to run the project:  
* numpy
* scikit-learn
* seaborn
* pandas
* matplotlib
Easiest way to add library to project:  
```
#example
pip install numpy
```
## Author
Mateusz Pałucki
## More helpful information
[ericstrong.org](https://ericstrong.org/predicting-abalone-rings-part-1/)

