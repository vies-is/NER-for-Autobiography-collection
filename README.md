# NER for Autobiography collection

The repository represents code and comments created for Master Thesis at Riga Technical university (2024) that is dedicated to the topic of extraction and preliminary analysis of the named entities, especially of type "Location", from a collection representative of cultural heritage domain. The target of analysis is Autobiography Collection of the Archives of Latvian Folklore held by the Institute of Literature, Folklore and Art of the University of Latvia.

There are four main Jupyter Notebook** files holding relevant code, two in "Data" and two in "NER-experiments" folder. Of these, refer to "NER-experiments" to find a demonstration of fine-tuned transformers model (specifically, xlm-roberta-large-ner-hrl) on Latvian-language corpus, calculations of "enamex" named entity frequencies and other specifics from the workflow implemented at the final stage of the project.

For references see ipynb files. 

** Selection of Jupyter Notebook is justified by the intention of the thesis to showcase an investigation of the possibilities and challenges associated with the use of existing models and pipelines. For this, immediate commentary is indispensable.

## Description of the repository

"Data" folder:
1) File "Scraper.ipynb" contains scraper. Nota bene: practical application of this code is not recommended.
2) File "corpus-preparation_NLTK.ipynb": basic pre-processing and first visualizations of text corpora.
3) Txt and csv files with results.

"NER-experiments" folder:
1) "1_Test_NER-with-xlmroberta.ipynb": preparations for main extraction and analysis; creation of relevant files; other investigations, both used and left out of main experiments and final vision of the thesis.
2) "2_NER-with-xlmroberta.ipynb": demonstration of final form of functions used to extract and analyse information relevant for and employed in development of the main arguments used at the thesis.
3) Csv files with test and final results.

Considering the limits of repository and other reasons, the following groups are main types of data added to gitignore: 1) most of the corpora; 2) model, software and data; 3) docx and xlxs files created for three texts selected for close reading; 4) files irrelevant for public access.
