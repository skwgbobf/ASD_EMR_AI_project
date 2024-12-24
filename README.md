# ASD_EMR_AI_project

# ASD Early Detection and Behavioral Analysis Project

This repository is for the `ASD Early Detection and Behavioral Analysis Project`, which aims to improve the diagnosis of Autism Spectrum Disorder (ASD) using advanced Natural Language Processing (NLP) models and machine learning techniques to support early intervention and personalized care.

## Project Objectives
- **ASD Classification**: Utilize QCHAT-10 to classify toddlers as either Typically Developing (TD) or at high risk for ASD using a fine-tuned RoBERTa model.
- **Behavioral Pattern Identification**: Use BERTopic modeling, GPT-3.5 Turbo + DSM-5 Retrieval-Augmented Generation (RAG), and OpenAI embeddings to identify nuanced behavioral patterns from clinical notes.

## Key Features
- **Early ASD Detection**: RoBERTa model fine-tuned on QCHAT-10 data to distinguish between TD and high-risk ASD cases.
- **Behavior Pattern Identification**: Advanced NLP techniques such as BERTopic, GPT-3.5 Turbo, and DSM-5 RAG are employed to extract distinct behavior patterns related to ASD.
- **Integration with Clinical Workflows**: Summarization tools reduce documentation burdens, allowing clinicians to focus on personalized interventions.

## Visual Workflow
- **ASD Classification Workflow**: Uses QCHAT-10 data and advanced deep learning techniques to classify toddlers, emphasizing early identification.
- **Behavior Identification Workflow**: Utilizes summarization and embeddings to extract clinically relevant behavioral patterns, highlighting both sensory-communication nuances and atypical engagement.

![Workflow Diagram](https://github.com/skwgbobf/ASD_EMR_AI_project/commit/64965003167e21f5244a3ece00a2965875695f0a)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/skwgbobf/ASD_EMR_AI_project.git
    cd ASD-ai-project
    ```

2. Install the necessary dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
This repository provides scripts for training, evaluating, and utilizing NLP models for ASD classification and behavior mapping. The following main approaches are included:

1. qchat10_screening_support : **RoBERTa-based QCHAT Classification**:
    - Fine-tune the model on QCHAT-10 data to classify toddlers into TD or high-risk ASD.
  
2. ASD_treatment_plan_support : **ASD Behavioral Pattern Identification**:
    - Apply BERTopic modeling along with GPT-3.5 Turbo for identifying specific behavioral spectrums such as "Sensory-Communication Nuances."

