# Fine-tuning
This repository presents the findings and conclusions of the final project of the course ``Natural Language Processing II", done by final year students of the Degree in Mathematical Engineering and Artificial Intelligence at ICAI. 

The main objective is to explore the fine-tuning of a pretrained language model for natural language processing tasks, focusing on efficiency in resource-constrained environments. Therefore, this project aims to address techniques such as Parameter-Efficient Fine-Tuning (PEFT) and model quantization, in order to be able to compress and optimize the base model using a single GPU with a 24-hour training limit. 

## Structure
In this repository can be found the following main files/directories:
- model_finetune_and_compression.ipynb: Main file in the repo. Contains the code to import the model, preprocess the data and perform the fine-tune.
- optuna.ipynb: Contains the code to perform Optuna to search for hyperparameters. In this case it was not able to go through a second trial, so we hardcoded the hyperparameters.
- evaluation/: Contains all documents needed for evaluation of the model.
- results/: Contains the results of the evaluation.
- instruction_following_eval/: Contains the responses of the model to the IFEval prompts.

## Authors
[Alejandro Martínez de Guinea García](https://github.com/xAlexMGGx)

[Javier Prieto Domínguez](https://github.com/javiprietod)
