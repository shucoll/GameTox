<h1 font-size:40px align="center">GameTox</h1>

This repository contains the data for our paper **<a href="https://aclanthology.org/2025.naacl-short.37/">GameTox: A Comprehensive Dataset and Analysis for Enhanced Toxicity Detection in Online Gaming Communities</a>** published at NAACL 2025.

## Abstract

The prevalence of toxic behavior in online gaming communities necessitates robust detection methods to ensure user safety. We introduce *GameTox*, a novel dataset comprising 53K game chat utterances annotated for toxicity detection through intent classification and slot filling. This dataset captures the complex relationship between user intent and specific linguistic features that contribute to toxic interactions. We extensively analyze the dataset to uncover key insights into the nature of toxic speech in gaming environments. Furthermore, we establish baseline performance metrics using state-of-the-art natural language processing and large language models, demonstrating the dataset’s contribution towards enhancing the detection of toxic behavior and revealing the limitations of contemporary models. Our results indicate that leveraging both intent detection and slot filling provides a significantly more granular and context-aware understanding of harmful messages. This dataset serves as a valuable resource to train advanced models that can effectively mitigate toxicity in online gaming and foster healthier digital spaces. The dataset and resources to reproduce the experiments are available at https://github.com/shucoll/GameTox.

## Annotation terminology

### Intent Classification
|  Class | Terminology | 
| :--------: | :--------: | 
| Non-Toxic | 0 | 
| Insults and Flaming | 1 | 
| Other Offensive Texts | 2 | 
| Hate and Harassment | 3 | 
| Threats | 4 | 
| Extremism | 5 | 

## Citation

If you decide to use this dataset, please cite the following paper:
<a href="https://aclanthology.org/2025.naacl-short.37/">GameTox: A Comprehensive Dataset and Analysis for Enhanced Toxicity Detection in Online Gaming Communities</a>

```
@inproceedings{naseem2025gametox,
  title={GameTox: A Comprehensive Dataset and Analysis for Enhanced Toxicity Detection in Online Gaming Communities},
  author={Naseem, Usman and Shiwakoti, Shuvam and Shah, Siddhant Bikram and Thapa, Surendrabikram and Zhang, Qi},
  booktitle={Proceedings of the 2025 Conference of the Nations of the Americas Chapter of the Association for Computational Linguistics: Human Language Technologies (Volume 2: Short Papers)},
  pages={440--447},
  year={2025}
}
```
