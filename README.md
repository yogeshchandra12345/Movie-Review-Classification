# Movie-Review-Classification
Movie Review Classification using IMDB dataset and Keras

We’ll work with the IMDB dataset: a set of 50,000 highly polarized reviews from the Internet Movie Database.

They’re split into 25,000 reviews for training and 25,000 reviews for testing, each set consisting of 50% negative and 50% positive reviews.

We'll use 10,000 most frequently occurring words in the training data. Rare words will be discarded. This allows us to work with vector data of manageable size.

train_labels and test_labels are lists of 0s and 1s, where 0 stands for negative and 1 stands for positive:

## Model
##### Hidden layers = 2 with 16 neuron in each layer
##### Relu activation is used for hidden layer and sigmoid for final layer.
##### Using batch_size=512, epoch = 4 We get good Accuracy of around 88%
