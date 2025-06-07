# LM4SouthAsia-Survey
A curated list of papers and resources for language models (LLMs) for Low-Resourced Languages in South Asia

Despite the rise of large language models (LLMs), South Asian languages still struggle with limited resources, code-mixing, and diversity, making it necessary to develop inclusive resources for these languages. This repository brings together models, adaptation strategies, and resources on bias and evaluation to help bridge the gap. 

We aim to record and provide a structured overview of existing resources to promote future research work for improving NLP technologies in South Asia.  

This repository is organized into three main sections:

- **LLMs and Model Resources**
- **Adaptation and Fine-Tuning Techniques**
- **Bias and Evaluation in South Asian NLP**


## 1.  LLMs and Model Resources

### 1.1  Multilingual LLMs
- ***(IndicBART)*** - IndicBART: A Pre-trained Model for Indic Natural Language Generation [[paper]](https://aclanthology.org/2022.findings-acl.145.pdf)
- ***(AxomiyaBERTa)*** - AxomiyaBERTa: A Phonologically-aware Transformer Model for Assamese [[paper]](https://aclanthology.org/2023.findings-acl.739.pdf)
- ***(IndicBERT)*** - IndicNLPSuite: Monolingual corpora, evaluation benchmarks and pre-trained multilingual language models for Indian languages. [[paper]](https://aclanthology.org/2020.findings-emnlp.445.pdf)
- ***(IndicBERTv2)*** - Towards Leaving No Indic Language Behind: Building Monolingual
Corpora, Benchmark and Models for Indic Languages [[paper]](https://aclanthology.org/2023.acl-long.693.pdf)
- ***(IndicTrans)*** - Samanantar: The Largest Publicly Available Parallel Corpora Collection for 11 Indic Languages [[paper]](https://aclanthology.org/2022.tacl-1.9.pdf)
- ***(IndicTrans2)*** - IndicTrans2: Towards High-Quality and Accessible Machine Translation Models for all 22 Scheduled Indian Languages [[paper]](https://arxiv.org/pdf/2305.16307)
- ***(Indic-ColBERT)*** - IndicIRSuite: Multilingual dataset and neural information models for Indian languages. [[paper]](https://aclanthology.org/2024.acl-short.46.pdf)
- ***(RelateLM)*** - Exploiting language relatedness for low web-resource language model adaptation: An indic languages study [[paper]](https://aclanthology.org/2021.acl-long.105.pdf)
- ***(HindiLLM-Small, HindiLLM-Medium)*** - HindiLLM: Large Language Model for Hindi [[paper]](https://arxiv.org/pdf/2412.20357)
- ***(Tri-Distil-BERT, Mixed-Distil-BERT)*** - Mixed-Distil-BERT: Code-mixed Language Modeling for Bangla, English, and Hindi [[paper]](https://arxiv.org/pdf/2309.10272v2)
- ***(TigerLLM)*** - TigerLLM - A Family of Bangla Large Language Models [[paper]](https://arxiv.org/pdf/2503.10995)
- ***(MahaBERT)*** - L3Cube-MahaCorpus and MahaBERT: Marathi Monolingual Corpus, Marathi BERT Language Models, and Resources [[paper]](https://aclanthology.org/2022.wildre-1.17.pdf)
- ***(CPT-R, IFT-R)*** - RomanSetu: Efficiently un-locking multilingual capabilities of large language models via Romanization [[paper]](https://aclanthology.org/2024.acl-long.833.pdf)

  
### 1.2  Task-Specific Fine-Tuned Models
- ***(BUQRNN, PN-BUQRNN)*** - Application of Quantum Recurrent Neural Network in Low-Resource Language Text Classification [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10461108)
- ***(DC-LM)*** - The best of both worlds: Dual Channel LM for Hope Speech Detection in low-resourced Kannada [[paper]](https://aclanthology.org/2022.ltedi-1.14.pdf)
- ***(Nepali DistilBERT, Nepali DeBERTa)*** - Nepali Encoder Transformers: An Analysis of Auto Encoding Transformer Language Models for Nepali Text Classification [[paper]](https://aclanthology.org/2022.sigul-1.14.pdf)
- ***(EmojiPredictor)*** - Predicting multi-label emojis, emotions, and sentiments in code-mixed texts using an emojifying sentiments framework [[paper]](https://www.nature.com/articles/s41598-024-58944-5)
- ***(Hindi-WMT)*** - Multimodal Machine Translation for Low-Resource Indic Languages: A Chain-of-Thought Approach Using Large Language Models [[paper]](https://aclanthology.org/2024.wmt-1.79.pdf)
- ***(MAPE model)*** - Together We Can: Multilingual Automatic Post-Editing for Low-Resource Languages [[paper]](https://aclanthology.org/2024.findings-emnlp.634.pdf)
- ***(IndIE)*** - IndIE: A Multilingual Open Information Extraction Tool For Indic Languages [[paper]](https://aclanthology.org/2023.findings-ijcnlp.28.pdf)
- ***(LambaniNMT)*** - Machine translation for a very low-resource language – layer freezing approach on transfer learning [[paper]](https://aclanthology.org/2022.loresmt-1.7.pdf)
- ***(BASE, MED, RETRAIN)*** - Abstractive Hindi text summarization: A challenge in a low-resource setting [[paper]](https://aclanthology.org/2023.icon-1.58.pdf)

  
### 1.3  Domain-Specific Models
- ***(MedSumm)*** - MedSumm: A Multimodal Approach to Summarizing Code-Mixed Hindi-English Clinical Queries [[paper]](https://arxiv.org/pdf/2401.01596)
- ***(AI-Tutor)*** - AI-Tutor: Interactive Learning of Ancient Knowledge from Low-Resource Languages [[paper]](https://aclanthology.org/2024.wat-1.5.pdf)
- ***(TPPoet)*** - TPPoet: Transformer-Based Persian Poem Generation using Minimal Data and Advanced Decoding Techniques [[paper]](https://arxiv.org/pdf/2312.02125)


## 2.  Model Adaptation Methods & Learning Strategies

### 2.1  Code-mixed Adaptations
- Mixed-Distil-BERT: Code-mixed Language Modeling for Bangla, English, and Hindi [[paper]](https://arxiv.org/pdf/2309.10272v2)
- MedSumm: A Multimodal Approach to Summarizing Code-Mixed Hindi-English Clinical Queries [[paper]](https://arxiv.org/pdf/2401.01596)
- Predicting multi-label emojis, emotions, and sentiments in code-mixed texts using an emojifying sentiments framework [[paper]](https://www.nature.com/articles/s41598-024-58944-5)


### 2.2  Supervised Multilingual Transfer Learning
- Samanantar: The Largest Publicly Available Parallel Corpora Collection for 11 Indic Languages [[paper]](https://aclanthology.org/2022.tacl-1.9.pdf)
- IndicTrans2: Towards High-Quality and Accessible Machine Translation Models for all 22 Scheduled Indian Languages [[paper]](https://arxiv.org/pdf/2305.16307)
- AxomiyaBERTa: A Phonologically-aware Transformer Model for Assamese [[paper]](https://aclanthology.org/2023.findings-acl.739.pdf)
- Overlap-Based Vocabulary Generation Improves Cross-Lingual Transfer Among Related Languages


### 2.3  Distillation and parameter-efficient finetuning (PEFT)
- Mixed-Distil-BERT: Code-mixed Language Modeling for Bangla, English, and Hindi [[paper]](https://arxiv.org/pdf/2309.10272v2)
- Nepali Encoder Transformers: An Analysis of Auto Encoding Transformer Language Models for Nepali Text Classification [[paper]](https://aclanthology.org/2022.sigul-1.14.pdf)
- Adapting Multilingual LLMs to Low-Resource Languages with Knowledge Graphs via Adapters [[paper]](https://aclanthology.org/2024.kallm-1.7v2.pdf)
- Cross-Lingual Named Entity Recognition for Low-Resource Languages: A Hindi-Nepali Case Study Using Multilingual BERT Models [[paper]](https://aclanthology.org/2024.mrl-1.12.pdf)
- BenLLM-Eval: A Comprehensive Evaluation into the Potentials and Pitfalls of Large Language Models on Bengali NLP [[paper]](https://aclanthology.org/2024.lrec-main.201.pdf)
- Quality or Quantity? On Data Scale and Diversity in Adapting Large Language Models for Low-Resource Translation [[paper]](https://aclanthology.org/2024.wmt-1.128.pdf)
- Large Language Models as a Normalizer for Transliteration and Dialectal Translation [[paper]](https://aclanthology.org/2025.vardial-1.5.pdf)
- Abstractive Summarization of Low resourced Nepali language using Multilingual Transformers [[paper]](https://aclanthology.org/2025.chipsal-1.12.pdf)
- Cost-Performance Optimization for Processing Low-Resource Language Tasks Using Commercial LLMs [[paper]](https://aclanthology.org/2024.findings-emnlp.920.pdf)
- IndiText Boost: Text Augmentation for Low Resource India Languages [[paper]](https://arxiv.org/pdf/2401.13085)
- Table Question Answering for Low-resourced Indic Languages [[paper]](https://aclanthology.org/2024.emnlp-main.5.pdf)

## 3.  Bias, Fairness & Evaluation

### 3.1  Sociocultural Bias in NLP
### 3.2  Evaluation Metrics
