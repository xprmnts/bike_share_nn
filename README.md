# Objective
To apply a simple neural network to model and predict bike sharing dataset.

# Hyperparameters

1) Learning rate: 0.75
- Played with values between 0.1 and 0.75, there didn't seem to be a significant difference between 0.4-0.75, perhaps if I ran a large volume of experiments I'd see a more clear deliniation between higher and lower learning rates.

2) Epochs: 5000
- I found that 5000 iterations was short enough for the model to converge, I experimented with upto 10000 iterations and it didn't seem to affect the resuls significantly and may have lead to overfitting.

3) Hidden Nodes: 10
- 10 nodes is about 1/2 the number of inputs and that should be okay, any less would bias and underfit the data and any more would slow down the execution time and it doesn't seem that it would make a significant difference for this dataset and model.

# Some outcomes: Keeping 5000 Epochs & 10 Hidden Nodes
1) Learning Rate: 0.75: 0.053 | 0.160
2) Learning Rate: 0.50: 0.062 | 0.140
