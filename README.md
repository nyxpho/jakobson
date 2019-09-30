# Discovering the Functions of Language in Online Forums, WNUT@EMNLP 2019


In this work, we revisit the functions of language proposed by linguist Roman Jakobson and we highlight their potential in analyzing online forum conversations. We investigate the relation between functions and other properties of comments, such as controversiality. We propose and evaluate a semi-supervised framework for predicting the functions of Reddit comments. To accommodate further research, we release a corpus of 165K comments annotated with their functions of language.


The repository contains two files: golden.txt and predicted.txt. 
The file golden contains the gold labels given by human annotators, while predicted contains the labeled predicted by our framework. 
Each file contains comments with the following json structure: 
1. "Func_label": 
"R" - referential
"P" - phatic
"E" - emotive
"O" - poetic
"C" - conative
"M" - metalingual
  

2. "id"
3. "parent_id"
4. "permalink"
