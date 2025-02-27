# Multimodal NLP - Visual Word Sense Disambiguation (Visual-WSD) - SemEval-2023

This repository contains a baseline to solve Visual Word Sense Disambiguation (V-WSD) and the script to evaluate the results for the V-WSD.
Our task is that given a word and some limited textual context, the task is to select among a set of ten candidate images the one which corresponds to the intended meaning of the target word. The dataset encompasses three languages: English, Italian, and Farsi. Each input includes a word, its context, and ten distinct images associated with the word. The objective is to establish the output by jointly analyzing the word and context, pinpointing the appropriate image among the ten provided that accurately correlates with our given word and context. To validate the accuracy of the output, a golden_text file is employed, containing the correct image name from the ten images that are appropriately associated with our specified word and context.
the details of the task and the provided dataset can be found in below link ;
https://raganato.github.io/vwsd/


Task: Given a word and some limited textual context, the task is to select among a set of candidate images the one which corresponds to the intended meaning of the target word.

Example: Given the full phrase andromeda tree containing the ambiguous target word andromeda, and the following ten candidate images, the task is to select the corresponding one. In this case, the correct image is the first one on the left, as shown below.
