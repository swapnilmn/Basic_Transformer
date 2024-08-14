# Transformer Model Implementation

This repository contains a custom implementation of the Transformer model using PyTorch. The Transformer, introduced in the paper "Attention is All You Need", is pivotal for various NLP tasks such as translation, summarization, and text generation. This project implements the model from scratch, focusing on its core components like Multi-Head Attention, Position-Wise FeedForward networks, and Positional Encoding.



## Features

- **Multi-Head Attention**: Splits the attention mechanism into multiple heads to capture different representation subspaces at different positions.
- **Positional Encoding**: Injects some information about the relative or absolute position of the tokens in the sequence.
- **Layer Normalization**: Normalizes the inputs across the features instead of the batch dimension to stabilize the learning process.
- **Configurable Architecture**: Easily adjustable parameters for the model's size, number of layers, and heads.


