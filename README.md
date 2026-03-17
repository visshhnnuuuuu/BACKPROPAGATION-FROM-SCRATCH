# BACKPROPAGATION-FROM-SCRATCH
Backpropagation lets a neural network learn by sending error backward. It computes how each weight caused the error and adjusts them using gradients, improving predictions step by step over time.
Backpropagation is the method a neural network uses to learn from its mistakes by adjusting its weights and biases. Imagine the network makes a prediction, compares it to the correct answer, and computes an error using a loss function. That error is not just a number—it carries information about how wrong the prediction is.

Now comes the clever part. Instead of guessing how to fix each weight, backpropagation uses the chain rule from calculus to trace the error backward through the network. It calculates how much each weight contributed to the final error. This is done layer by layer, starting from the output layer and moving toward the input layer.

For each layer, it computes gradients, which are essentially directions and magnitudes indicating how to change the weights to reduce the error. Once these gradients are known, an optimization algorithm like gradient descent updates the weights by slightly nudging them in the opposite direction of the error.

Over many iterations, the network keeps adjusting itself, gradually improving its predictions. In essence, backpropagation is how a neural network turns feedback into learning, transforming raw numerical adjustments into meaningful pattern recognition over time.
