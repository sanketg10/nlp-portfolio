# nlp-portfolio
Collection of my projects in sentiment analysis, translation, hmm, speech recognition etc. 

__Project 1:__ Using Pomegranate library in Python to perform HMM analysis for POS tagging etc. Next step is to use CRFs.

__Project 2:__ Using encoder-decoder RNNs to perform machine translation. It performs pretty well actually.
Initially we used many-to-many RNNs without encoder-decoder networks to perform translation. Lengths of English and French
sentences have to be exactly same in this case. But with encoder-decoder networks lengths can be different.
Also learnt about using `TimeDistributed` layer in Keras. Next step is to use attention models or BERT.

__Project 3:__ Built CNN + RNN models to detect the spectrograms of speech and detect the patterns to guess the words.
Next step is to use Language model at the decoder level. 

Other folders have labs and other collection of practice workbooks etc that went along with the NLP Udacity nanodegree. 
