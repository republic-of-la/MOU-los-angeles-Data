Los Angeles MOU Analysis Project

Overview

This project is designed to analyze and extract key information from Memorandums of Understanding (MOU) related to the City of Los Angeles. By utilizing advanced language models, this project aims to provide clear, factual answers to specific questions about various policies, benefits, and procedures outlined in these government documents.

Features

	•	Tokenized Analysis: Efficient tokenization of MOU content to ensure accurate analysis and processing.
	•	Automated Question Answering: Automatically answers questions related to the MOU, such as salary steps, vacation accruals, and other employee benefits.
	•	Data Processing: Includes custom scripts to process and format the MOU data for fine-tuning language models.
	•	Fine-Tuning: Leveraging language models to fine-tune specific outputs that align with the structure and requirements of civil government documentation.

How It Works

	1.	Data Ingestion: PDF documents of MOUs are ingested and converted into text format.
	2.	Token Counting: Text from each section of the MOU is tokenized to measure and control input sizes for the language model.
	3.	Fine-Tuning: The language model is fine-tuned with specific questions and answers derived from the MOU content, ensuring the model can accurately respond to inquiries about the document. (huggingface models)
	4.	Automated Response Generation: The fine-tuned model generates responses to predefined questions, offering clear and concise information.

Getting Started

Prerequisites

	•	Python 3.8+
	•	PyTorch
	•	Transformers (Hugging Face)
	•	Pandas

 

