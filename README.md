# Shakespeare Models

This repository contains the code to train two models to generate Shakespearean text. the first model is a fine-tuning of the GPT-2 model and the second one a LSTM model.

Both models use the same dataset which is a collection of Shakespeare's plays. The dataset can be found in the root folder in a file called `text.txt`. The dataset is from Kaggle and can be found [here](https://www.kaggle.com/code/aashkatrivedi/shakespeare-text-generation/input).

## Project goal and motivation

The motivation behind this project is to explore the capabilities of language models and their applications in generating text. The problem we are trying to solve is the task of generating coherent and contextually relevant text that resembles the style and structure of a given literary work, in this case, the works of William Shakespeare.

By training these models on a corpus of Shakespearean literature, we aim to leverage their language modeling abilities to generate new text that captures the essence of Shakespeare's writing style.

## Reproducing the results

I would highly recommend to do the training on `Google Colab` and to use a GPU. The code should also work on a CPU though, but it will take a considerable amount of time to train the models. For my run I chose the `A100` GPU from `Google Colab`.

The Validation notebook however can be run locally on your machine without any issues.
