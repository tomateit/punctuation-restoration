# Punctuation restoration

This is a research project on punctuation (commas, mostly) restoration methods.
First of all, I have big expectation from using seq2seq models, so I gonna use em first.

Refer to notebooks folder to see my pity attempts :)
- `notebooks/1-seq2seq_formulation`  - pretty decently working model based on lstm net (actually predicts if a word shall be followed by a comma).
- `notebooks/2-lstm_bidirectional` - same, as above, but bidirectional, so handles come cases much better.
- `notebooks/3-third-party` directly utilized code from https://github.com/vlomme/Bert-Russian-punctuation

The code in this repo is not intended for outside usage as third-party code. 
