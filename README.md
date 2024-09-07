# Text-to-SQL Model Project

This repository contains the complete code and resources for training and evaluating a text-to-SQL model using Meta-LLaMA-3.1-8B. The project focuses on generating SQL queries from natural language questions based on various database schemas.

## Contents

- **Results Data**: Includes the results from evaluating the model on 1,034 test samples. The results show both the actual and generated SQL queries, along with the schema and natural language question.

- **Jupyter Notebook**: A comprehensive notebook that covers the full workflow, including:
  - Data preprocessing
  - Fine-tuning the Meta-LLaMA-3.1-8B model
  - Model evaluation and results analysis

## Usage

### Training
Use the Jupyter notebook provided to preprocess your data and fine-tune the model. The notebook also includes instructions for setting up the environment and running the training process.

### Inference
Load the pre-trained model to generate SQL queries from natural language questions. The notebook provides examples for running inference and evaluating results.

### Results Analysis
Explore the results data to understand the model's performance across simple, moderate, and complex queries. The full table of results is available in the `results_data.csv` file.

## Requirements

To install the necessary dependencies, use the `requirements.txt` file:

```bash
pip install -r requirements.txt
