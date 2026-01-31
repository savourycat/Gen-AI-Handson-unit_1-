# Gen-AI-Handson-unit_1-
# Unit 1 – Generative AI Hands-On

## Key Concepts Gained
- Understood the architectural differences between encoder-only and encoder–decoder Transformer models.
- Learned how BERT and RoBERTa use Masked Language Modeling (MLM) to capture contextual meaning in text.
- Explored how BART performs sequence-to-sequence tasks, making it suitable for generation-based applications.
- Practiced using Hugging Face pipelines for text generation, fill-mask prediction, question answering, and summarization.
- Recognized the importance of fine-tuning for improving performance on task-specific NLP problems.

## Solution Implementation

### Assignment: Model Benchmarking
Three experiments were conducted to compare **BERT**, **RoBERTa**, and **BART** on the following tasks:
1. Text Generation  
2. Fill-Mask Prediction  
3. Question Answering  

The performance and outputs of each model were analyzed, and the observed results were explained based on their underlying architectures and design goals.

### Project: TL;DR for News Articles
A text summarization system was implemented using the **Hugging Face summarization pipeline** with the  
`bart-large-cnn` model.  

The system takes long news articles as input and generates concise, meaningful summaries that capture the key points of the text.

## Conclusion
These hands-on experiments provided practical insight into how different Transformer architectures behave across various NLP tasks. The project also demonstrated how pretrained Hugging Face models can be effectively leveraged to quickly build real-world Generative AI applications with minimal effort.

