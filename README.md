
# AI-Based Phishing Detection in Email

**Bachelor's thesis project by Tansin Habib**  
Bachelor of Information Technology, Centria University of Applied Sciences · May 2025

This project explores deep learning techniques for classifying email messages as phishing or legitimate. It combines academic research with a Jupyter Notebook covering dataset preparation, text preprocessing, model training, and evaluation.

## Project Materials

- **[Open the Jupyter Notebook](./ai_based_phishing_detection_combined_bert_lstm.ipynb)** — implementation and experiments.
- **[Read the Thesis](./AI-Based%20Phishing%20Detection%20in%20Email.docx)** — research background, methodology, results, limitations, and future directions.

## Objectives

- Investigate how deep learning can identify phishing patterns in email text.
- Prepare labelled email data for binary classification.
- Explore sequence-based and Transformer-based approaches.
- Evaluate model performance and consider limitations for email security.

## Methodology

1. **Dataset collection:** The notebook downloads the `naserabdullahalam/phishing-email-dataset` dataset using KaggleHub.
2. **Preprocessing:** Email text is cleaned and normalized, with URLs and contact details handled according to the notebook's pipeline.
3. **Data splitting:** The thesis describes training, validation, and test subsets.
4. **Modeling:** The research discusses LSTM-based and Transformer/BERT approaches.
5. **Evaluation:** Performance is assessed using metrics such as accuracy, precision, recall, F1-score, and AUC, along with visualizations where implemented.

## Reported Result

The thesis abstract reports **98.75% accuracy for the LSTM model**. It also notes that the BERT approach showed promise but required additional data and fine-tuning.

This is the result reported in the thesis, not a guarantee of performance on new or real-world emails. Run the notebook to evaluate the models in your own environment.

## Tech Stack

- Python
- TensorFlow / Keras
- KaggleHub
- pandas and NumPy
- scikit-learn
- Matplotlib and Seaborn
- Jupyter Notebook / Google Colab

## Getting Started

1. Open the [Jupyter Notebook](./ai_based_phishing_detection_combined_bert_lstm.ipynb).
2. Download it or open it in Google Colab.
3. Follow the notebook's setup instructions and install its dependencies.
4. Configure Kaggle access if prompted.
5. Run the cells in order and review the evaluation results.

Deep-learning training may require substantial memory and computing resources. A GPU-enabled notebook environment can help.

## Repository Contents

- `ai_based_phishing_detection_combined_bert_lstm.ipynb` — data preparation, model training, and evaluation.
- `AI-Based Phishing Detection in Email.docx` — thesis document.
- `resourse/` — supporting resources.
- `.vscode/` — editor configuration.

## Limitations and Responsible Use

This is an academic research and portfolio project, not a production email security product. Results depend on dataset composition, preprocessing, and training configuration. High test accuracy does not guarantee detection of unseen or adversarial phishing messages. Do not use this model as the sole defence for real email accounts or systems.

## Author

**Tansin Habib**

[GitHub Profile](https://github.com/tansinhabib26)
