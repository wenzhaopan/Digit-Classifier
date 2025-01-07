# Overview
Neural network with back propagation implemented and 3 hidden layers to identify handwritten digits from the MNIST dataset with approximately 97% accuracy. 

# Getting started
Make sure to `pip install torch torchvision matplotlib`.

Run the following code block to train the network and test it:

```python
for epoch in range(1, 11):
    train(epoch)
    test()
