# Large-Language-Model-Evaluation

## Introduction
This repository contains the code and documentation for evaluating various language models for sentiment analysis. The project explores different approaches, including lexicon-based methods, classical machine learning algorithms, customized word embeddings, fine-tuning pre-trained language models (PLMs), and a hybrid approach combining multiple methods. 

## About the Project
The primary objective of this project is to assess the performance of different techniques in sentiment analysis using IMDb movie reviews dataset. The evaluation includes measuring accuracy, precision, recall, F1 score, and other relevant metrics to determine the effectiveness of each approach.

## Repository Structure
- **Code**: Contains Python scripts for implementing different approaches and evaluating language models.
- **Data**: Includes the IMDb movie reviews dataset used for training and testing the models.
- **Results**: Stores the results obtained from each approach, including accuracy scores, confusion matrices, and other evaluation metrics.
- **Documentation**: Consists of detailed reports and README files explaining each approach, methodology, and findings.

## Setup Instructions
1. Clone the repository to your local machine:
git clone https://github.com/your-username/LLMs-Evaluation.git
2. Install the required dependencies
3. Navigate to the specific approach directory within the `Code` folder and execute the Python scripts to run the evaluation.

## Approach Overview
### 1. Lexicon-based Approach
- Utilizes lexicon-based sentiment analysis tools such as SentiWordNet and AFINN.
- Semi-supervised learning strategy combining lexicon-based scores with traditional machine learning techniques.
- Results compared based on accuracy and computational efficiency.

### 2. Classical Machine Learning Approaches
- Implements Naive Bayes, Random Forest, Support Vector Machine (SVM), and Gradient Boosting Machine (GBM).
- Evaluation based on accuracy, training time, and model complexity.

### 3. Customized Word Embeddings
- Implements Word2Vec for generating word embeddings.
- Comparison of different machine learning models trained on Word2Vec vectors.

### 4. Fine-tuning Pre-trained Language Models (PLMs)
- Fine-tunes DistilBERT, RoBERTa, and GPT-2 for sentiment analysis.
- Evaluation includes accuracy, training time, and performance metrics.

### 5. Hybrid Approach
- Integrates lexicon-based, machine learning, word embedding, and PLM-based methods.
- Ensemble approach combining predictions from multiple models for enhanced accuracy.

## Results and Conclusion
The repository contains detailed reports and analysis for each approach, along with comparative assessments and conclusions drawn from the evaluation. Results highlight the strengths and limitations of each method and provide insights into their effectiveness for sentiment analysis tasks.

## Contributor
- [Syed Umer](https://github.com/syedumeerr)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



