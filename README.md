# Bangla Currency Note Classification and Usability Assessment

This repository provides the complete implementation of a deep learning-based system for automated classification and usability analysis of Bangladeshi currency notes. It includes a two-part pipeline:

1. **Currency Classification** — Identifies the denomination of banknotes using multiple deep learning models including a lightweight custom CNN.
2. **Damage Detection and Usability Analysis** — Assesses the physical condition of a note through alignment, binary mask comparison, feature integrity analysis, and color degradation scoring.


## Features

* Combined dataset of 82k+ images from 3 public sources
* Preprocessing pipeline with deduplication, enhancement, and augmentation
* Classification using VGG16, ResNet50, EfficientNetB0, InceptionV3, and a custom CNN
* Image alignment using SIFT, FLANN, and RANSAC
* Usability scoring with edge, corner, feature, and color damage quantification
* Frontend built with Streamlit for easy deployment


## Note

We are currently working on improving the system and expanding the dataset for broader usability scenarios. The full codebase and data will be released publicly once the work is published as a paper.

---

© 2025 Md Sultanul Islam Ovi

