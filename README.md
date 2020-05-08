# abstractive summary and title generation
 Corner stone seq2seq with attention (using bidirectional ltsm )
#### the model
  - uses an encoder with multi layer RNN with LSTM
  - Decoder is built using bahadau attention model
  - Inference was cstom built by hand
  #### Data is 
  - arxivscraper research papers
  #### Word2Vec
  - Conceptnet Numberbatch's (CN) embeddings, similar to GloVe, but probably better 
  (https://github.com/commonsense/conceptnet-numberbatch)
