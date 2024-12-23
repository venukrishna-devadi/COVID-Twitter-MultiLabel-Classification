# COVID-Twitter Multi-Label Classification 🚀  
Analyzing and classifying public health messages on COVID-19 from Twitter using state-of-the-art NLP techniques and models.  

---

## 📜 Project Overview  
This project focuses on classifying COVID-19-related tweets into multiple public health categories such as prevention, symptoms, outbreak, vaccines, and travel updates. By leveraging advanced Natural Language Processing (NLP) models and techniques, this work contributes to real-time public health monitoring and the dissemination of critical information.  

---

## ✨ Key Features  
- **Multi-Label Classification**: Developed pipelines to categorize tweets into multiple overlapping public health themes.  
- **State-of-the-Art Models**: 
  - **BERT** for contextual embeddings.  
  - **CNN-GRU**, **TCN**, and ensemble approaches for sequence modeling.  
- **Imbalanced Data Handling**: 
  - Implemented strategies like stratified sampling and weighted class adjustments to improve performance.  
  - Used TF-IDF with SVM as a baseline for comparison.  
- **Performance**: Achieved:  
  - **F1 score of 0.88** for binary classification.  
  - **F1 score of 0.76** for multi-label classification tasks.  

---

## 📊 Dataset  
- **Source**: Tweets collected from verified public health Twitter accounts such as `@CDCgov`, `@CDCemergency`, and others using the Tweepy API.  
- **Timeframe**: December 25, 2020 – April 1, 2021.  
- **Annotations**: 
  - Binary labels indicating whether tweets are related to COVID-19.  
  - Five detailed categories for multi-label classification:  
    - Prevention  
    - Symptoms  
    - Outbreak  
    - Vaccines  
    - Travel  

---

## 🛠️ Project Structure  

- **Data Preprocessing**: Includes filtering, tokenization, and feature extraction using TF-IDF and lexicons.  
- **Models Implemented**:  
  - BERT-based models for contextual embeddings.  
  - Sequence models like CNN, GRU, TCN, and LSTM.  
  - Ensemble models combining CNN and GRU/TCN for robust predictions.  
- **Code Files**:  
  - `BERT_Binary_Classification_Class_Weight.ipynb`: Binary classification using BERT with weighted classes.  
  - `MLP_Binary_Text_Classification_Using_TCN.ipynb`: Binary classification with TCN.  
  - `MLP_MultiClass_Classification_Class_Weight.ipynb`: Multiclass classification with weighted losses.  
  - `Text_Classification_Using_Ensemble_CNN_GRU.ipynb`: Ensemble model for robust classification.  
  - And more files exploring various model architectures.  

---

## 🔑 Results  
- **Binary Classification**:  
  - Best Model: TF-IDF with SVM.  
  - F1 Score: **0.88**.  

- **Multi-Label Classification**:  
  - Best Model: CNN-GRU Ensemble.  
  - F1 Score: **0.76**.  

- **Key Insights**:  
  - Lexicon features improved category-specific performance.  
  - Addressing imbalanced datasets through sampling and class weights was critical.  

---

## 📖 About the Author  
I’m **Venu Gopal Krishna Devadi**, a graduate student specializing in **Data Science** at Saint Peter’s University. My interests lie in **Natural Language Processing**, **Transformer Models**, and applying **Deep Learning** to solve real-world challenges.  

### Other Relevant Projects  
- **Multilingual Language Translator**: Transformer-based model translating English to Hindi and Telugu.  
- **Anime Character Image Classification**: Using EfficientNet B2 for advanced image recognition.  
- **Machine Learning Doubt Clarifier Chatbot**: Leveraging GPT and T5 models for ML query resolution.  

### Publications  
- **"Infodemic Management using Natural Language Processing: A COVID-19 Case Study"**  
  Presented at AMIA 2024 Annual Symposium – P157, San Francisco, CA.  

- **"Information Management using Natural Language Processing: A COVID-19 Case Study"**  
  Accepted in *Advances in Healthcare using Machine Learning*, Taylor and Francis.  

---

## 🔗 Connect with Me  
- **Email**: venukrishnadevadi@gmail.com  
- **LinkedIn**: [linkedin.com/in/venu-devadi-2350b3252](https://linkedin.com/in/venu-devadi-2350b3252/)  

---

## 🛠️ Getting Started  

### Prerequisites  
- Python 3.7+  
- Libraries: `pandas`, `numpy`, `tensorflow`, `torch`, `sklearn`, `tweepy`, `matplotlib`  

### Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/COVID-Twitter-MultiLabel-Classification.git
   cd COVID-Twitter-MultiLabel-Classification

2. Install required libraries:  
   pip install -r requirements.txt
   
## 📂 Repository Files
Notebooks: Code for binary and multi-label classification.
Data: Scripts to preprocess and load data.
Results: Visualization of model performance metrics.

## 🚀 Future Work
Extend to a broader dataset, including unverified accounts.
Experiment with zero-shot classification techniques.
Explore explainability techniques to enhance model transparency.

Feel free to fork, star ⭐, and contribute to this repository! 😊
