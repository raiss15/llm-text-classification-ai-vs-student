# 🧠 AI vs Student Text Classification using BERT

A fine-tuned BERT model that classifies whether a paragraph was generated by an AI language model or written by a student. This project also includes a polished Streamlit web app for real-time text classification.

[![Hugging Face](https://img.shields.io/badge/model-BERT--base--uncased-blue?logo=huggingface)](https://huggingface.co/bert-base-uncased)
[![Streamlit App](https://img.shields.io/badge/Live%20Demo-Streamlit-green?logo=streamlit)](#)

## 📌 Project Overview

- **Objective**: Detect and classify text as AI-generated or student-written
- **Model**: `bert-base-uncased`, fine-tuned using Hugging Face Transformers
- **Dataset**: Kaggle – [LLM Detect AI vs Student Dataset](https://www.kaggle.com/datasets/prajwaldongre/llm-detect-ai-generated-vs-student-generated-text)
- **Frontend**: Streamlit-based UI for live classification
- **Result**: Achieved 100% accuracy on test set with full precision, recall, and F1-score

## How to Run the Project

## 1. Clone the Repository

git clone https://github.com/your-username/llm-text-classification.git
cd llm-text-classification

## 2. Install Dependencies

pip install -r requirements.txt

## 3. Launch the Streamlit App

streamlit run streamlit_llm_demo_final.py

## 🎨 Streamlit Web App Features

✍️ Paste any paragraph → AI predicts "AI" or "Student"
🔍 Shows confidence score from softmax output
🧑‍🏫 Intuitive design with emoji feedback
📘 Sidebar: dataset info, model overview, credits
✅ Easy to run or deploy via Streamlit Cloud

## 🔬 Future Enhancements

- Add explainability via SHAP or LIME
- Include adversarial testing and style mimicry
- Expand dataset with GPT-4, Claude, etc.
- Build a browser extension or LMS plugin for educators

## 🧾 License

This project is licensed under the MIT License.

## 👩‍💻 Author
Sohni Rais
Graduate Student, M.S. in Information Systems
Northeastern University, Boston

