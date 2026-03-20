## English-German-Neural-Machine-Translation-via-BLEU-evaluation.
Developed a Neural Machine Translation model using Keras/TensorFlow, demonstrating end-to-end NLP pipeline design and performance evaluation with BLEU metrics. Future improvements can be integrating Attention mechanisms/ Transformer models.

## Features

End-to-end English to German translation pipeline

Tokenization & Padding for sequence preprocessing

Pre-trained word embeddings (FastText & GloVe)

Bidirectional LSTM Encoder + Decoder architecture

Beam Search decoding for improved predictions

Built using Keras with TensorFlow backend

## Model Architecture

Embedding Layer: Converts words into dense vector representations

Encoder: Bidirectional LSTM capturing contextual information

Decoder: LSTM for generating translated sequences

Dense Layer: Maps outputs to target vocabulary

# Evaluation

Metric Used: BLEU Score

## Achieved:

High training accuracy (~99%)

Low BLEU score → highlights generalization challenges

## Challenges

Overfitting due to limited dataset

Low real-world translation quality despite high accuracy

Lack of attention mechanism in baseline model

## Future Work

Integrate Attention Mechanism / Transformer models

Use larger and more diverse datasets

Apply regularization techniques

Improve evaluation with multiple metrics


## Key Highlights

Built with Keras + TensorFlow

Uses FastText & GloVe embeddings

Implements tokenization, padding, and beam search decoding

Trained on 20k sentence pairs

## Results

~99% training accuracy

Low BLEU score → highlights generalization challenges

## Limitations

Overfitting due to limited data

No attention mechanism

## Future Improvements

Add Attention / Transformer models

Use larger datasets

Improve evaluation metrics
