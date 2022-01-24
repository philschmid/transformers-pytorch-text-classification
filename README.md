# Pytorch Text-classification with distributed training

Welcome to our end-to-end multilingual Text-Classification example using PyTorch. In this demo, we will use the Hugging Faces `transformers` and `datasets` library together with `Pytorch` fine-tune a multilingual pre-trained transformer for text-classification. 

This Repository contains to Notebooks: 

* [text-classification](text-classification.ipynb) a step-by-step example on how fine-tune a multilingual Transformer for text-classification
* [sagemaker-distributed-training](sagemaker-distributed-training.ipynb) a derived version of the first notebook, which shows how to scale your training for distributed training using Amazon SageMaker.