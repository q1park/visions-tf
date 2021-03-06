# Convolutional networks in tensorflow

With all of the insanity going on due to the merging of Keras and Tensorflow, I thought it would be nice to provide several examples of ways to build models that satisfy the following requirements:

1) They work in Tensorflow 1.13
2) They work in Tensorflow 2.0
3) They don't require Keras standalone

Each example has an increasing level of customizability:

flowers-tf-kerasgeneric.ipynb - Simplest example of a sequential ConvNet using model.fit

flowers-tf-kerascustom.ipynb - Subclassing tf.keras.Model for increased flexibility

flowers-tf-kerasfree.ipynb - Building models from scratch with minimal reliance on API's

flowers-torch.ipynb - Equivalent example using PyTorch

The following module gives an example of how to load data into Tensorflow models using tf.data.Dataset or just purely with numpy arrays

imageloader.py

Other random stuff:

batchtest.ipynb - Time/memory tests for various batching procedures
