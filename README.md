# ImageCaptioning

Using Flickr8k dataset since the size is 1GB. MS-COCO is 14GB!

Used Keras with Tensorflow backend for the code. InceptionV3 is used for extracting the features.

I am using Beam search with k=3, 5, 7 and an Argmax search for predicting the captions of the images.

The loss value of 1.5987 has been achieved which gives good results. You can check out some examples below. The rest of the examples are in the jupyter notebook. You can run the Jupyter Notebook and try out your own examples. unique.p is a pickle file which contains all the unique words in the vocabulary.

Everything is implemented in the Jupyter notebook which will hopefully make it easier to understand the code.
