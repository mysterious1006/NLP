📧 Insurance Claim Email Classification System

An end-to-end Natural Language Processing (NLP) pipeline that classifies insurance claim emails into multiple categories using a fine-tuned BERT transformer.

This project demonstrates the complete workflow from data preprocessing → tokenization → model training → evaluation, making it ideal for real-world NLP applications.

🚀 Features

🔍 Multi-class email classification using BERT

⚡ End-to-end NLP pipeline

🧹 Data preprocessing using Pandas

🔡 Tokenization using Hugging Face Tokenizers

🤖 Fine-tuned Transformer model (BERT)

📊 Performance evaluation with Accuracy & F1-score

🏋️ Training using Hugging Face Trainer API

🛠️ Tech Stack

Programming Language: Python

Libraries & Frameworks:

Hugging Face Transformers

PyTorch

Scikit-learn

Pandas

NumPy

📂 Project Structure
Insurance-Email-Classifier/
│
├── data/                   # Dataset files
├── notebooks/              # Jupyter notebooks (EDA & experiments)
├── src/
│   ├── preprocessing.py    # Data cleaning & preprocessing
│   ├── tokenizer.py        # Tokenization pipeline
│   ├── model.py            # BERT model setup
│   ├── train.py            # Training script
│   ├── evaluate.py         # Evaluation metrics
│
├── outputs/                # Model checkpoints & results
├── requirements.txt        # Dependencies
├── README.md               # Project documentation
⚙️ Installation

Clone the repository:

git clone https://github.com/your-username/insurance-email-classifier.git
cd insurance-email-classifier

Install dependencies:

pip install -r requirements.txt
📊 Dataset

Contains insurance-related emails categorized into multiple classes such as:

Claim Request

Claim Status

Policy Inquiry

Complaint

Others

⚠️ Note: Dataset is not included due to privacy concerns. You can use your own dataset in CSV format.

🔄 Workflow

Data Preprocessing

Cleaning text (removing noise, special characters)

Handling missing values

Tokenization

Using Hugging Face BERT tokenizer

Padding & truncation

Model Training

Fine-tuning pretrained BERT

Using Trainer API

Evaluation

Accuracy

F1-score

Confusion Matrix

🧠 Model Details

Base Model: bert-base-uncased

Architecture: Transformer-based encoder

Training Framework: Hugging Face Trainer API

Loss Function: Cross-Entropy Loss

📈 Results
Metric	Score
Accuracy	XX%
F1 Score	XX%

Replace XX with your actual results.

▶️ Usage

Run training:

python src/train.py

Run evaluation:

python src/evaluate.py
📌 Future Improvements

🔹 Deploy as a REST API using Flask/FastAPI

🔹 Add real-time email classification

🔹 Improve dataset size and diversity

🔹 Experiment with advanced models (RoBERTa, DistilBERT)

🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit a pull request.

📜 License

This project is licensed under the MIT License.

👨‍💻 Author

Shaurya Pratap Singh
