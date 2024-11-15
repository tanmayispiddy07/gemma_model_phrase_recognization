# Phrase Generation using Gemma 2bit Model

This project demonstrates the use of the Gemma 2bit model for phrase generation tasks. The model is trained using a dataset of tweets and evaluated on multiple test files, including a zero-shot test file. The tokenizer used is `AutoTokenizer` from Hugging Face.

## Project Overview

The objective of this project is to generate relevant phrases based on the input data (tweets) using the Gemini 2bit model. The model is evaluated in two primary tasks:
1. **Stance Detection**: Identifying the stance of the tweet towards the given target.
2. **Target Generation**: Generating the target (topic) from the tweet content.

The model has been tested on several datasets with results indicating its effectiveness in handling various scenarios, including zero-shot tasks.

## Model

The **Gemini 2bit model** is a state-of-the-art transformer-based model that excels in natural language processing tasks, particularly in generating meaningful phrases from textual input. It is fine-tuned for both stance detection and target generation tasks in this project.

### Tokenizer

- **Tokenizer**: `AutoTokenizer` from Hugging Face, used to preprocess the input data for the model.

## Files and Directories

### Data
- **Training Dataset**:
  - `train_random_32.csv`: The training dataset consisting of random samples of 32 tweets.
- **Test Datasets** (3 files): 
  - `case1.csv`
  - `case2.csv` 
  - `zero_shot_test.csv`: A zero-shot test dataset for evaluating the model's performance on unseen data.

### Model and Tokenizer
- **Model**: Gemini 2bit model for phrase generation.
- **Tokenizer**: `AutoTokenizer` from Hugging Face.

## Installation

Follow these steps to set up the environment and run the code:

clone the repo into google colab and set the storage as Hard Disk or else 
 Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
```
## Evaluation Metrics

The performance of the model is evaluated using the following metrics for both tasks:

### Stance Detection
- **Case 1**: 78% accuracy
- **Case 2**: 78% accuracy
- **Zero-shot**: 60% accuracy

### Target Generation
- **Case 1**: 78% accuracy
- **Case 2**: 79% accuracy
- **Zero-shot**: 64% accuracy



## Conclusion

This project demonstrates the ability of the **Gemini 2bit model** to generate relevant phrases based on tweet data. It shows strong performance across both stance detection and target generation tasks. The zero-shot evaluation results highlight the model's ability to generalize well to unseen data.



## Acknowledgments

- Gemini 2bit model and Hugging Face's **`AutoTokenizer`**.
- Dataset and test files for phrase generation tasks.
