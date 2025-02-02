# Assignment_Topsis_For_Pretrained_Models_Text_Summarization_102217105
## Title
Topsis For Pretrained Text Summarization Models 102217105
## Methodology

## Description
1. Different models: BART, PEGASUS, T5, LEAD5, BERT are trained on the 
   same dataset.
2. They are evaluated on basis of ROUGE Values:<br>
   ROUGE-1 (Unigram Precision, Recall, F1):
   Gives more importance to matching unigrams (individual words) between 
   the generated summary and the reference summary.<br>
   ROUGE-2 (Bigram Precision, Recall, F1):
   Gives more importance to matching bigram between the generated summary 
   and the reference summary.<br>
   ROUGE-L (Longest Common Subsequence):
   ROUGE-L focuses on the longest common subsequence and is considered 
   useful for capturing longer phrases and word sequences. 
3. Apply Topsis and calculate topsis score.
4. Rank accordingly.

## Project Structure:
INPUT FILE (input_model_parameters.csv): The CSV file containing value of parameters for differnt models.<br>
OUTPUT FILE (result.csv): The csv file obtained after applying topsis containing topsis score and rank.<br>
GRAPHS (Models_vs_Topsis and Models_vs_Parameters): Charts visualising topsis score comparision and comparision of all parameter values for different models respectively.

## Result and Analysis:
Topsis Score and Rank obtained in result.csv
Bar Graphs: Visual representation of performance metrics for each model and its topsis score.
