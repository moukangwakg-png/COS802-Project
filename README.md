# COS802 Project - Cross-Lingual Transfer Learning for Kinyarwanda Semantic Relatedness
This repository is for an NLP project completed for the course module COS802 with the University of Pretoria, South Africa

📋 PROJECT OVERVIEW

**Objective**: This repository contains the code and analysis for investigating cross-lingual transfer learning from English to Kinyarwanda for semantic relatedness tasks. The project explores zero-shot transfer capabilities of multilingual models (LaBSE, XLM-R and AFROXLM-R) and the effects of translation-based data augmentation. This is executed in Python, and best suited for the Google Colab environment (an attempt at generalisation for application in other environments has been made)

**Key Finding**: Pre-trained LaBSE embeddings outperform fine-tuned versions, challenging conventional fine-tuning practices for low-resource languages.

📁 REPOSITORY Files

2.1. Kinyarwanda_Semrel.ipynb # Main executable notebook with results and visualisations

2.2. Kinyarwanda_Translation_ipynb # Supplementary notebook for translation from English to Kinyarwanda

2.3. translated_kin_train.csv #Translated Kinyarwanda data for augmentation (output from 2.2)

2.4. requirements.txt #List of libraries required to run the code files

2.5. README.md #This file, with the instructions

🚀 QUICK START
Prerequisites: 
Jupyter compatible environment (Google Colab is ideal but any should do)
Python libraries as per requirements.txt

Running the Analysis:
1. Install packages: `pip install -r requirements.txt`
2. Start Jupyter: `jupyter notebook`
3. Open `kinyarwanda_SemRel.ipynb` and click "Cell → Run All"

📋 DATA
- Uses the English and Kinyarwanda subsets of the SemRel2024 dataset from Hugging Face (https://huggingface.co/datasets/SemRel/SemRel2024)
- Data is loaded directly using the Hugging Face 'datasets' library. No manual loading is required.
