# example-documents
This repository contains the documents that are used as examples in my BA thesis.  
All documents stand under the "Data licence Germany – attribution – version 2.0".

Each folder contains the selected document as well as the most similar document found by each of the models.
The documents are named accordingly. 

Examples of how the documents are labeled:
"example-4-selected-document": The document that was selected.
"example-4-found-document-elastic": The document that was found by elastic.
"example-4-found-document-doc2vecc-4": The document that was found by the model Doc2VecC 4.
"example-4-found-document-doc2vecc-1-and-2-and-3-and-5": The document that was found by the models Doc2VecC 1, Doc2VecC 2, Doc2VecC 3, Doc2VecC 5.

The models are:
Elastic:    The Elasticsearch "more like this" query.
Doc2VecC 1: Model with the hyperparameter configuration used in the original example
Doc2VecC 2: Model with a smaller context window size (compared to the original configuration)
Doc2VecC 3: Model with a higher negative sampling rate (compared to the original configuration)
Doc2VecC 4: Skip-gram model (all other models use CBOW)
Doc2VecC 5: Model with a higher corruption rate (compared to the original configuration)


