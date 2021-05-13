# `HopeSpeechDetection`
## Our  work on hope speech detection task organized by LT-EDI-2021.
In this task we have used various pretrained transformer models for transfer learning as well as cross lingual inferencing .
The dataset is pretty imbalanced.
Different methodologies to address the class imbalance were being used in our experiments.
The models used for the experiments are:
i) IndicBERT
ii) mBERT-cased
iii) XLM-Roberta
iv) BERT-base-cased (English)
v) BERT-base-uncased (English)

In order to reproduce the results you can clone this repository and set your dataset paths in the training scripts.

Our results for the hope speech detection task

![image](https://user-images.githubusercontent.com/42090593/118063283-667fbf80-b3b6-11eb-96bf-63224bb0aa20.png)


If you find our work useful do consider citing our paper.
```
@inproceedings{ghanghor-etal-2021-iiitk-lt,
    title = "{IIITK}@{LT}-{EDI}-{EACL}2021: Hope Speech Detection for Equality, Diversity, and Inclusion in {T}amil , {M}alayalam and {E}nglish",
    author = "Ghanghor, Nikhil  and
      Ponnusamy, Rahul  and
      Kumaresan, Prasanna Kumar  and
      Priyadharshini, Ruba  and
      Thavareesan, Sajeetha  and
      Chakravarthi, Bharathi Raja",
    booktitle = "Proceedings of the First Workshop on Language Technology for Equality, Diversity and Inclusion",
    month = apr,
    year = "2021",
    address = "Kyiv",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/2021.ltedi-1.30",
    pages = "197--203",
    abstract = "This paper describes the IIITK{'}s team submissions to the hope speech detection for equality, diversity and inclusion in Dravidian languages shared task organized by LT-EDI 2021 workshop@EACL 2021. Our best configurations for the shared tasks achieve weighted F1 scores of 0.60 for Tamil, 0.83 for Malayalam, and 0.93 for English. We have secured ranks of 4, 3, 2 in Tamil, Malayalam and English respectively.",
}
```
