### PVGRU

The repository contains the code for PVGRU，the baseline for comparison, and SepaCVAE, where the code for SepaCVAE is provided by the original author of the paper [1].



### Attention

We employ an improved version of BLEU and ROUGE  in paper [2]. When using the BLEU function provided by NLTK with SmoothingFunction().method7, the results are improved by about 20 points. We provide a set of comparative results for reference.

Results of HRED

BLEU in paper: bleu-1: 0.2890 bleu-2: 0.2352 bleu-3:0.2103 bleu-4: 0.2019

NLTK BLEU: bleu-1: 0.4865 bleu-2: 0.3789 bleu-3: 0.3101 bleu-4: 0.2619



[1] Bin Sun, Shaoxiong Feng, Yiwei Li, Jiamou Liu, and Kan Li. 2021. Generating relevant and coherent dialogue responses using self-separated conditional variational autoencoders. In ACL.

[2] Yang A, Liu K, Liu J, et al. Adaptations of ROUGE and BLEU to Better Evaluate Machine Reading Comprehension Task.ACL 2018: 98-104.
