---
layout: single
permalink: /adaptive-learning-models/
title: "Adaptive Learning Models for Efficient and Standardized Archival Processes"
author_profile: true
redirect_from: 
  - /md/
  - /projects.html
---

## <span style="padding-left: 0.5rem;">Project Title: Adaptive Learning Models for Efficient and Standardized Archival Processes</span>

### Duration  
<span style="padding-left: 0.5rem;">January 2020 – "Ongoing"</span>

### Institution  
<span style="padding-left: 0.5rem;">Carl Albert Congressional Research and Studies Center Archives</span>

### Project Overview  
This project addresses the increasing demands placed on archival systems by large-scale digitization efforts and the complex metadata requirements that accompany them. By developing [**adaptive learning pipelines**](https://d197for5662m48.cloudfront.net/documents/publicationstatus/237538/preprint_pdf/705ddcb4d0e61842b2f21af4b5fea10e.pdf), the project enhances efficiency, accuracy, and repeatability in managing digitized historical documents, especially those relevant to American Indian policy, congressional records, and tribal sovereignty.

The model extracts meaningful metadata and enriches archival content using **Natural Language Processing (NLP)** and **machine learning** in an iterative, feedback-controlled environment.

---

### Technical Innovation  
A core innovation of this project is its **adaptive loop system** that combines multiple modules:

- **Preprocessing:** Automated OCR cleanup, diacritic analysis, format normalization  
- **Text Extraction & Entity Recognition:** Using AWS Textract, spaCy, and custom models  
- **Controlled Vocabulary Matching:** Real-time lookup against dynamic dictionaries  
- **Feedback Loops:** Enables metadata correction and training model refinement  
- **Contextual Matching Algorithms:** Enables inference for names, tribes, themes

<figure style="text-align: center; margin: 2rem 0;">
  <img src="/images/Figure_1_Controls_Adaptive.jpg" alt="Controls Diagram" style="max-width: 100%; height: auto;">
  <figcaption style="font-style: italic;">Figure 1. Adaptive controls for vocabulary and dictionary development.</figcaption>
</figure>

---

### Tools & Technologies  
- **NLP Libraries**: spaCy, TextBlob, NLTK  
- **OCR and Text Processing**: AWS Textract, Tesseract, Gensim  
- **Machine Learning**: Torch, Transformers  
- **Python APIs**: OpenAI, boto3, re, os, pandas  
- **Custom Classifiers**: For tribal affiliation, government functions, correspondence metadata  
- **Feedback Loop Engines**: Performance-aware batch revision triggers

<figure style="text-align: center; margin: 2rem 0;">
  <img src="/images/modelcompares-1.jpg" alt="Model Comparison Table" style="max-width: 100%; height: auto;">
  <figcaption style="font-style: italic;">Model evolution: comparative summary of core elements and performance.</figcaption>
</figure>

---

### Metrics and Performance

| Metric            | Purpose                                          | Example                                               |
|-------------------|--------------------------------------------------|--------------------------------------------------------|
| **Accuracy**      | Evaluate model precision and recall              | F1 Score ≈ 0.941 on 100-page test set                 |
| **Speed**         | Pages processed per minute                       | 20 pages/minute on 1,000-page batch                   |
| **Error Rate**    | % of incorrect assignments                       | 2.5% on 1,000 document test case                      |
| **Scalability**   | Handles small to large datasets dynamically      | Maintains >0.88 F1 score on 10,000-page loads         |

<figure style="text-align: center; margin: 2rem 0;">
  <img src="/images/Metrics and Calculations-2024.jpg" alt="Metric Table" style="max-width: 100%; height: auto;">
  <figcaption style="font-style: italic;">Performance metrics and model assessment framework.</figcaption>
</figure>

---

### Use Case: “Pleasant Porter” Entity Assignment  
This example illustrates how the adaptive model accurately linked a historical reference to Pleasant Porter with the correct tribe, region, and congressional records—without direct keyword matches—by triangulating date, sender location, and prior content relationships.

<figure style="text-align: center; margin: 2rem 0;">
  <img src="/images/Figure_2_PleasantPorter.jpg" alt="Pleasant Porter Matching Logic" style="max-width: 100%; height: auto;">
  <figcaption style="font-style: italic;">Conditional model logic for recognizing complex entity matches.</figcaption>
</figure>

---

### Resources and Tribal Authority Integration  
The project integrates language-specific dictionaries and subject matchers, including:

- **Tribal Directories**
- **Historic Treaties**
- **Language Dictionaries**
- **Culturally significant terminology mapping**

<figure style="text-align: center; margin: 2rem 0;">
  <img src="/images/Tribal-1.jpg" alt="Tribal Data Reference" style="max-width: 100%; height: auto;">
  <figcaption style="font-style: italic;">Language and tribal data integration resources used in contextual enrichment.</figcaption>
</figure>

---

### Outcomes

- Created standardized metadata for over **75,000 records**  
- Developed **3 evolving model pipelines** tested on real collections  
- Automated tribal recognition and subject assignment with high accuracy  
- Released public training materials and scripts via [GitHub](https://github.com/prys0000)  
- Framework adopted by the **Congressional Portal Project** and others

---

### Related Links

- [CAC ArchivesSpace](https://arc.ou.edu/)
- [Digital Archives Platform](https://oucac.access.preservica.com/)
- [Project GitHub](https://github.com/prys0000/congressional-portal-project)
- [Published Article](https://doi.org/10.1017/arcs.2024.64)

