# MuseHash: MuseHash: Supervised Bayesian Hashing for Multimodal Image Representation

Implementation of MuseHash, a novel supervised Bayesian hashing framework for multimodal image retrieval that extends the single-modality BiasHash (Bayesian ridge-based Semantic Preserving Hashing) approach. MuseHash utilizes Bayesian regression per modality to estimate semantic probabilities, generates binary hash codes, and fuses multiple modalities (such as visual, textual, spatial, and temporal data) into a unified image representation.

---

## 🚀 Getting Started
- Python 3.8+
- MongoDB
- BiasHash GitHub: https://github.com/mpegia/BiasHash

## ⚙️ Usage
- Preprocess and Extract Features: Navigate to the feature extraction module and execute the preprocessing pipeline to extract visual (e.g., ResNet50, VGG16) and textual/metadata feature vectors.
- Run the Multimodal Framework Pipeline: Execute the core framework scripts to train Bayesian ridge regression models per modality, generate binary hash codes, perform late fusion, and query the multimodal database.

## 📚 Acknowledgments & Reference

This work builds upon the BiasHash framework and was supported by the EU's Horizon 2020 research and innovation programme under grant agreements H2020-883302 (ISOLA) and H2020-101004152 (CALLISTO). 

If you use this code or framework in your research, please cite the original MuseHash paper:

Pegia, M., Jónsson, B. Þ., Moumtzidou, A., Gialampoukidis, I., Vrochidis, S., & Kompatsiaris, I. (2023). MuseHash: Supervised Bayesian Hashing for Multimodal Image Representation. In Proceedings of the ACM International Conference on Multimedia Retrieval (ICMR '23) (pp. 434–442). ACM.  

## 📜 License
This document is licensed under a Creative Commons Attribution 4.0 (CC BY-NC-SA) licence.
