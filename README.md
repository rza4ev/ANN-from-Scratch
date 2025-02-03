ANN-from-Scratch
In this post, I’ll walk you through the essential mathematical formulas behind training a neural network using forward and backward propagation, Xavier initialization, and the Adam optimizer.
Xavier Initialization: Proper weight initialization plays a crucial role in training deep networks. Xavier Initialization sets the weights based on the size of the input and output layers to help prevent vanishing/exploding gradients.

ReLU Activation: The Rectified Linear Unit (ReLU) activation function is used in hidden layers to introduce non-linearity, allowing the network to learn complex patterns.

Softmax Activation: For multi-class classification, the Softmax function converts raw output scores into probabilities, enabling the model to make class predictions.

Cross-Entropy Loss: The loss function calculates how well the model’s predictions match the true labels. In classification problems, we use cross-entropy loss to measure the error between predicted and actual class probabilities.

Adam Optimizer: Adam combines momentum and adaptive learning rates to efficiently optimize the model's parameters. It uses first and second moment estimates to improve convergence speed and stability.

Backpropagation: Gradients of the loss are computed using the chain rule, which helps in updating the weights during training.

Accuracy Calculation: The accuracy is measured by comparing the predicted classes with the true labels, providing a performance metric for the model.

