# NLP_HW-1
# CS5760 — NLP Homework 1 (Spring 2026)

## Student  
**Name:** NAGA MANEESH REDDY KONDA  
**ID:** 700773566  
**Course:** CS5760 Natural Language Processing  

---

## 📌 Project Overview  

This repository contains my solutions for **Homework 1** in Natural Language Processing, including:  

- **Q2 — Byte Pair Encoding (BPE)**  
  - Manual BPE analysis on a toy corpus  
  - Implementation of a mini BPE learner in Python  
  - Segmentation of words such as: `new`, `newer`, `lowest`, `widest`, `earnest`

- **Q5 — Tokenization in Telugu**  
  - Naïve space-based tokenization  
  - Manual tokenization with suffix handling (`లో, పై`)  
  - Tokenization using **Indic NLP Library**  
  - Comparison of the three approaches  
  - Identification of Multiword Expressions (MWEs) in Telugu  

The goal of this assignment is to understand how tokenization works across languages and how subword models like BPE help reduce the out-of-vocabulary (OOV) problem.

---

## 📁 Files in this Repository  

| File | Description |
|------|-------------|
| `NLP_HW-1_q2_bpe.ipynb` | Jupyter notebook for Q2: Manual BPE + Python BPE learner |
| `NLP_Homework_1.py` | Full Telugu tokenization pipeline for Q5 |
| `requirements.txt` | Required Python libraries |

---

## ▶️ How to Run the Code  

### **Step 1 — Install dependencies**

Run this in your terminal:

```bash
pip install -r requirements.txt
