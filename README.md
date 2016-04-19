# Project-Kojak
## Unsupervised text translator

This algorithm can be used to translate text from any language to any language, but I have used English and Spanish in my code. 

For this code to work, the input data has to be large articles in English and their corresponding Spanish translations. Each English paragraph with its corresponding Spanish paragaph need to be one document.
Eg: the board considered a draft decision submitted by the president idb l and adopted decision idb dec see annex i __la__ __junta__ __examinó__ __un__ __proyecto__ __de__ __decisión__ __presentado__ __por__ __el__ __presidente__ __idb__ __l__ __y__ __adoptó__ __la__ __decisión__ __idb__ __dec__ __véase__ __el__ __anexo__ __i__

In the above example second half is the corresponding translation of the English text (first half). Total_actual_docs in the code is a list of such paragraphs and is passed as input to the LSI model.
