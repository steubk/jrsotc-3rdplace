#  Kaggle  - Jigsaw Rate Severity of Toxic Comments - 3rd place solution

This is my 3st place solution of [Jigsaw Rate Severity of Toxic Comments](https://www.kaggle.com/c/jigsaw-toxic-severity-rating) Kaggle competition.

![](https://github.com/steubk/jrsotc-3rdplace/blob/main/sol.png?raw=true)

Specific writeup is [here](https://www.kaggle.com/c/jigsaw-toxic-severity-rating/discussion/306235).

Self-consistent notebook  of final submission is [here](https://www.kaggle.com/steubk/jrsotc-a-detoxify-solution-0-81299-3rd-place) 

In this repository you can find some experiments  I did during the competition.

## Environment

all notebooks run on [Kaggle/docker-python](https://github.com/Kaggle/docker-python) with additional packages:

```
pip install detoxify 
pip install transformers
pip install sentence_transformers
pip install iterative-stratification
```

## Datasets
Kaggle datasets to download in input directory
```
kaggle competitions download -c jigsaw-toxic-severity-rating
kaggle datasets download -d  rajkumarl/ruddit-jigsaw-dataset
kaggle datasets download -d  julian3833/jigsaw-unintended-bias-in-toxicity-classification
kaggle datasets download -d  julian3833/jigsaw-toxic-comment-classification-challenge
