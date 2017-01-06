# char-rnn-tensorflow with Speech
Speech based on Multi-layer Recurrent Neural Networks (LSTM, RNN) for character-level language models in Python using Tensorflow.

Sampled text output is converted to Speech and played.

Inspired from Andrej Karpathy's [char-rnn](https://github.com/karpathy/char-rnn).

# Requirements
- [Tensorflow](http://www.tensorflow.org)
- pygame
- mutagen
- gtts

# Basic Usage
To train with default parameters on the tinyshakespeare corpus, run `python train.py`.

To sample from a checkpointed model, `python sample.py`.

Tested on Anaconda Python 3.5 on Windows 10.
