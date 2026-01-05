# 🧠 Building a Domain Expert: Llama 2 7B Fine-Tuning on AWS 🚀

Welcome to the **Domain Expert Model** project! This repository demonstrates the power of **Generative AI** and **Transfer Learning** by transforming the general-purpose Meta Llama 2 7B model into a specialized expert in **Finance**, **Medical**, or **IT** domains.

## 🌟 Overview

Large Language Models (LLMs) are amazing generalists, but sometimes you need a specialist. This project takes the robust **Meta Llama 2 7B** and fine-tunes it using **AWS SageMaker JumpStart** on curated datasets. The result? A model that speaks the language of your chosen industry with greater fluency and accuracy.

## ✨ Key Features

*   **🎯 Domain Adaptation:** Customize Llama 2 for Finance, Medical, or IT sectors.
*   **☁️ Powered by AWS:** Leverages the scalability of AWS SageMaker for training and deployment.
*   **🛠️ End-to-End Workflow:** From baseline evaluation to fine-tuning and final deployment.
*   **📉 Efficient Training:** Uses techniques like LoRA (Low-Rank Adaptation) via SageMaker JumpStart.
*   **📊 Comparative Analysis:** Evaluate the "before and after" to see the tangible benefits of fine-tuning.

## 🔄 The Workflow

1.  **🚀 Setup & Initialization**: Configure your AWS environment and install necessary libraries (`sagemaker`, `datasets`, `boto3`).
2.  **🧐 Baseline Evaluation**: Deploy the stock Llama 2 7B model. Test it with specialized prompts to see its initial limitations.
3.  **🏋️ Fine-Tuning**:
    *   Select your target domain (Finance, Medical, or IT).
    *   Feed the model domain-specific datasets stored in S3.
    *   Train the model using SageMaker's powerful GPU instances (`ml.g5.2xlarge`).
4.  **📈 Expert Evaluation**: Deploy your newly minted expert model. Run the same prompts and witness the improvement in response quality and domain knowledge.
5.  **🧹 Cleanup**: Efficiently tear down resources to optimize costs.

## 🛠️ Tech Stack

*   **Python 3.10+**
*   **AWS SageMaker** & **Boto3**
*   **Meta Llama 2 7B**
*   **Hugging Face Transformers & Datasets**
*   **PyTorch**

## 🚀 Getting Started

### Prerequisites
*   AWS Account with SageMaker access.
*   Proper IAM roles configured.
*   Python environment.

### Installation

Clone the repo and install the dependencies:

```bash
git clone <repo-url>
cd <repo-name>
# Install dependencies as seen in the notebooks
pip install sagemaker datasets ipywidgets boto3
```

## 📖 Usage

This project is divided into two main Jupyter Notebooks:

1.  **`Model Evaluation/Model_Evaluation_UdacityGenAIAWS.ipynb`**: Start here! Evaluate the base model.
2.  **`Fine Tuning/Model_FineTuning.ipynb`**: The main event. Fine-tune the model on your chosen dataset and re-evaluate.

### 🎥 Visuals from the Project

**Fine Tuning Process:**
![Fine Tuning](Fine%20Tuning/Fine%20Tuning.png)

**Model Evaluation:**
![Model Evaluation](Model%20Evaluation/Model%20Evaluation.png)

**Submission Confirmation:**
![Submission Confirmation](Project%20Report/Submission%20Confirmation.png)

---
*Built with ❤️ for the Udacity Generative AI with AWS Nanodegree.*
