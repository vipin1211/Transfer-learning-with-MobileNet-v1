# Transfer-learning-with-MobileNet-v1

In this notebook, we will leverage transfer learning on a pre-trained CNN to build an Alpaca/Not Alpaca classifier!

We'll use, MobileNetV2, which was designed to provide fast and computationally efficient performance. It's been pre-trained on ImageNet, a dataset containing over 14 million images and 1000 classes.

By the end of this, we will be able to:

Create a dataset from a directory

Preprocess and augment data using the Sequential API

Adapt a pre-trained model to new data and train a classifier using the Functional API and MobileNet

Fine-tune a classifier's final layers to improve accuracy
