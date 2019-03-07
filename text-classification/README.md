This repository contains binary text classification using different NLP models and compare the performance.

# Overview
Generalized NLP models have been improved recently and could be used with less effort in retraining the model for specific usage. This repository uses fixed model data for all the models and compare the performance of the base models without any fine tuning. The data used is from one of the kaggle competition (https://www.kaggle.com/c/word2vec-nlp-tutorial/data)

# Performance of different Models



			| Model  		| Performance 	|
			| --------------------- | ------------- |
			| HAN			| 0.85624  	|
			| ELMO  		| 0.83420  	|
			| ULMFIT  		| 0.92960  	|
			| BERT  		| 0.92116  	|

# Model Diagrams
## HAN

![HAN Word Encoder model](word-encoder.png?raw=true "HAN Word Encoder model")

![HAN Sentence Encoder model](sentence-encoder.png?raw=true "HAN Sentence Encoder model")


## ELMO

![ELMO model](elmo.png?raw=true "ELMO model")
