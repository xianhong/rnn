# Learn a simple RNN model to use three words to predict the next one. 
# The work is inspired by a post (http://www.brightideasinanalytics.com/rnn-pretrained-word-vectors/).
The work adopts mini-batch training to improve training efficiency (The original post uses single sample stochastic traing .) `tf.data` is used to build traing pipelines. 
`glove.6B.300d.txt` is available at http://nlp.stanford.edu/data/glove.6B.zip

