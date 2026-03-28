# AI-900 Cheat Sheet (Microsoft Azure AI Fundamentals)

This cheat sheet covers all key concepts, service mappings, and exam patterns needed to pass the AI-900 exam.

---

# 1️⃣ Machine Learning Basics

## Types of ML

| Problem | Type |
|---|---|
Predict number | Regression |
Predict category | Classification |
Group data | Clustering (Unsupervised) |

---

## Key Terms

| Term | Meaning |
|---|---|
Features | Inputs |
Labels | Output |

---

## Metrics (VERY IMPORTANT)

| Metric | Use |
|---|---|
Accuracy | Overall correctness |
Precision | Avoid false positives |
Recall | Avoid false negatives |
F1 Score | Balance of precision + recall |

**Important:**
- Medical / fraud → Recall
- Spam filtering → Precision

---

# 2️⃣ Core Azure AI Services

| Task | Service |
|---|---|
Build ML models | Azure Machine Learning |
Text analysis | Azure AI Language |
Image analysis | Azure AI Vision |
Speech/audio | Azure AI Speech |
Chatbots | Azure Bot Service |
Generative AI | Azure OpenAI |

---

# 3️⃣ Exact Feature Mapping (MOST IMPORTANT)

## 🟣 Text (Azure AI Language)

| Scenario | Feature |
|---|---|
Sentiment detection | Sentiment Analysis |
Extract key phrases | Key Phrase Extraction |
Identify entities | Named Entity Recognition (NER) |
FAQ bot | Question Answering (QnA) |
Conversation intent | CLU |

---

## 🔵 Vision

| Scenario | Feature |
|---|---|
Detect objects | Object Detection |
Tag images | Image Tagging |
Describe images | Captioning |
Read text | OCR |
Custom model | Custom Vision |

---

## 🟢 Documents

| Scenario | Feature |
|---|---|
Invoices/receipts | Document Intelligence (prebuilt models) |
Forms/tables | Layout Model |

---

## 🟡 Speech

| Scenario | Feature |
|---|---|
Speech → text | Speech-to-Text |
Text → speech | Text-to-Speech |
Speech translation | Speech Translation |

---

## 🟠 Machine Learning (Azure ML)

| Scenario | Feature |
|---|---|
No-code ML | ML Designer |
Auto model selection | AutoML |
Dev environment | Compute Instance |
Large training | Compute Cluster |

---

## 🔴 Generative AI

| Scenario | Feature |
|---|---|
ChatGPT apps | GPT models (Azure OpenAI) |
Embeddings | Embedding models |

---

# 4️⃣ Most Asked Exam Scenarios

| Question | Answer |
|---|---|
FAQ bot | Language – Question Answering |
Sentiment analysis | Language – Sentiment |
Image detection | Vision – Object Detection |
Read text in image | Vision – OCR |
Invoice extraction | Document Intelligence |
Speech transcription | Speech-to-Text |
Train ML model | Azure ML |
Drag-drop ML | ML Designer |
Auto ML | AutoML |
Chatbot | Bot Service |
Generative AI | Azure OpenAI |

---

# 5️⃣ Responsible AI Principles

| Principle | Meaning |
|---|---|
Fairness | No bias |
Reliability | Consistent results |
Privacy | Protect data |
Transparency | Explain decisions |
Accountability | Responsibility |
Inclusiveness | Usable by all |

---

# 6️⃣ Exam Pattern Tricks

## Trick 1

| If question says | Answer |
|---|---|
Prebuilt AI APIs | Azure AI Services |
Custom ML models | Azure Machine Learning |

---

## Trick 2

| Keyword | Answer |
|---|---|
Image | Vision |
Text | Language |
Speech | Speech |
Chatbot | Bot Service |
GPT | OpenAI |

---

## Trick 3

| Scenario | Focus |
|---|---|
Medical / fraud | Recall |
Spam filtering | Precision |

---

# 7️⃣ Common Confusions

| Confusion | Correct Answer |
|---|---|
Vision vs Custom Vision | Prebuilt vs Custom |
OCR vs Document Intelligence | Simple text vs structured data |
Language vs Translator | Analysis vs translation |
Bot vs QnA | Chat framework vs FAQ knowledge |

---

# 8️⃣ Quick Memory Block

Regression → number  
Classification → category  
Clustering → grouping  

Features → input  
Labels → output  

Recall → don’t miss positives  
Precision → don’t raise false alarms  

Vision → images  
Language → text  
Speech → audio  
ML → models  
Bot → chat  
OpenAI → generative AI  

