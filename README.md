# Mental Health Severity Prediction using DistilBERT

## Overview

This repository contains the code and resources for a project that fine-tunes the DistilBERT language model on a mental health dataset. The model is designed to take text input from a person and predict the severity of their mental health condition.

## Table of Contents

- [Project Overview](#overview)
- [Dataset](#dataset)
- [Model](#model)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Dataset

The dataset used in this project includes various text inputs from individuals experiencing mental health issues. The data is labeled to indicate the severity of the condition. Key files include:
- `Mental Health Dataset.csv`: Contains the main dataset.
- `Student Mental health.csv`: Contains additional data points.
- `global_mentalhealth/`: Directory with global mental health data.
- `mental_health.csv`: Another supplementary dataset.

## Model

The core of this project is the fine-tuning of the DistilBERT model. DistilBERT is a smaller, faster, and cheaper version of BERT that retains 97% of BERT's language understanding capabilities. The fine-tuning process involves training DistilBERT on the provided mental health datasets to improve its ability to assess the severity of mental health conditions based on text input.

## Installation

To run this project, ensure you have the following prerequisites installed:

- Python 3.6 or higher
- Jupyter Notebook
- Git

Clone the repository and install the required packages:

```sh
git clone https://github.com/your-username/Hacathon.git
cd Hacathon
pip install -r requirements.txt
