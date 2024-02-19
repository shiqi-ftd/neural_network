# neural_network playbook 

First class of https://karpathy.ai/zero-to-hero.html

Everything is covered so nicely in https://www.youtube.com/watch?v=VMj-3S1tku0 given by Karpathy

Source code of micrograd: https://github.com/karpathy/micrograd

To succinctly outline the backpropagation process in a Multilayer Perceptron (MLP - feedforward artificial neural network):

- Forward Pass: Compute the current loss using the existing weights (w) and biases (b) for each neuron across all layers.

- Backward Pass: Determine the gradient for each neuron's weights and biases. Note the error: failure to reset the gradient (p.grad = 0) led to unintended accumulation from previous iterations.

- Update Phase: Adjust the weights and biases incrementally, using the negative gradient multiplied by the learning rate, to minimize the overall loss function.

- Repeat :)


