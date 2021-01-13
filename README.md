###Status: Unfinished

# Healthcare Text Classification through NLP using Tensor-flow and Keras Part 1.

## Introduction

The healthcare industry produces and stores large qunatities of data on a daily basis. The amounts and type of data vary greatly in size and type, therefore often the data is unsorted, uncategorized and the content data is unclean. This poses great difficulties when trying to work with the data and doing cleaning for analysis. In this case, a neural net based text classification program would greatly benefit into categorizing data into different groups. Fast tracking different analytics processes and making retrieval easier. 

In this notebook I am going to build a simple neural net based on natural language processing concepts, using google's Tensorflow and the Keras library to build and train a neural network, based on a data-model from Doctor reports. 

The purpose is to classify these reports to different Hospital departments, or disease descriptions based on the report given by the doctor or nurse, in order to make data cleaning easier. Furthemore this model can be used for data cleaning through transfer-learning and included into an automated cleansing-script. 

In the future, this data model can be used and paired with OCR technology to convert legacy or unsupported filetypes, or capture data from incompatible healthcare data-sharing systems. 

The dataset we are using was scraped from https://www.mtsamples.com/, which hosts collection of transcribed medical transcription sample reports and examples. 

### Exploring NLP Text Classification of Healthcare data

The NLP application of the posed problem in this notebook will be demonstrating text classification. Here we will explore categorizing medical text documents into one of a predefined set of topics/labels. In many topic classification problems, this categorization is based primarily on keywords in the text. 
