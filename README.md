# ITS530-RLHF-TLDR-Sentiment
A GPT-2 RLFH trained to make reddit posts more positive using multiple versions of distilbert for its reward function

## Dataset:
Contains:
- Data-Creation code
- Full TLDR Sentiment dataset
- Small TLDR Sentiment dataset

## With IMDB Reward function:
this folder has the model trained using the imdb distilbert in the reward function
Contains:
- The model files after training
- the code used to make the model

## With my own reward function:
this folder has the model created using the reward function i made (it performs poorly)
Contains:
- code used to train the reward function model
- code used to train the GPT-2 using the tldr distilbert as reward
- multiple variations using different dataset sizes due to memory constraints
