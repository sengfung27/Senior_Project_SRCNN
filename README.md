# Senior_Project_SRCNN

Tensorflow implementation of Convolutional Neural Networks for super-resolution. Base on paper:
  * [Learning a Deep Convolutional Network for Image Super-Resolution](http://personal.ie.cuhk.edu.hk/~ccloy/files/eccv_2014_deepresolution.pdf)
  * [Image Super-Resolution Using Deep Convolutional Networks](https://arxiv.org/pdf/1501.00092.pdf)
  * [Accelerating the Super-Resolution Convolutional Neural Network](https://arxiv.org/pdf/1608.00367.pdf)
  * [Real-Time Single Image and Video Super-Resolution Using an Efficient Sub-Pixel Convolutional Neural Network](https://arxiv.org/pdf/1609.05158.pdf)


## Documentation

[Click here](https://github.com/edwin0108/Senior_Project_SRCNN/tree/master/doc) for more information of our project. 



## Prerequisites

- Python 3.5.x (since `Tensorflow-gpu` only support up to python 3.5.x)
- Tensorflow.Keras ([click here to learn about tensorflow.keras](https://colab.research.google.com/github/tensorflow/docs/blob/master/site/en/guide/keras.ipynb#scrollTo=9NR6reyk0E2A) and [click here for keras documentation](https://keras.io/))



## Dataset

For now, please use `91-images` as our train dataset and `set5` as our validation dataset as they are  relatively small (you can find them at data folder). We will use `DIV2K` dataset for final evaluation.
