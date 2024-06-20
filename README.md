# QAMaster: Fine-tuned Q/A Chat Box

## Overview
This project creates a Q/A chat box using multiple pre-trained models. It fine-tunes these models on a Q/A dataset and evaluates them to choose the best one based on F1-score and Exact Match.

## Models Used
- QWEn-1.5.72B (Local)
- Scientific Research (Local)
- gpt2
- BERT for QuestionAnswering
- deepset/roberta-base-squad2

## Steps
1. Setup Environment
2. Load Pre-trained Models
3. Fine-tune the Models
4. Evaluate the Models
5. Choose the Best Model

## Requirements
- transformers
- datasets
- torch
- evaluate
