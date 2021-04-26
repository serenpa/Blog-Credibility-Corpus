# Blog-Credibility-Corpus
The blog credibility corpus is a dataset to aid the credibility assessment of blog articles written by software practitioners. The dataset was preseted at [EASE 2021](https://www.ntnu.edu/ease2021).For more information, please refer to the paper or contact the authors.

## Format of the dataset
The file ```blog_credibility_dataset.tsv``` contains 19996 sentences. The annotations consist of 3 tags that label elements of argumentation (Claim, Reasoning, Conclusion) and 7 tags that label types of evidence. The columns are as follows:

- **ID**: a unique identifier for the sentence
- **Document_ID**: a unique identifier for the blog article that the sentence originates from
- **Sentence_ID**: a indentifier of the sentence within the document and indicator of its order
- **Sentence_Text**: the sentence that has been annotated
- **Claim**: a binary indicator of whether the sentence contains a claim
- **Reasoning**: a binary indicator of whether the sentence contains any reasoning
- **Conclusion**: a binary indicator of whether the sentence contains any conclusions
- **Citation**: a binary indicator of whether the sentence contains any citations/links to external content 
- **Code Snippet**: a binary indicator of whether the sentence contains any code snippets
- **Events**: a binary indicator of whether the sentence contains any events
- **Experience**: a binary indicator of whether the sentence contains any mentions of experience
- **Reference to Table/Image**: a binary indicator of whether the sentence references any tables or images
- **Statistics/Data**: a binary indicator of whether the sentence references any data or statistics
- **Other**: a binary indicator of whether the sentence contains any other form of evidence that is not covered by the above labels

**Please refer to the paper for full definitions**

## Licence
The dataset is released under the [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) licence.

## Citation
Please cite the following paper in your work when using the dataset:

*Williams, A., Shardlow, M. and Rainer, A., 2021. Towards a corpus for credibility assessment in software practitioner blog articles. In Procedings of the 25th International Conference on Evaluation and Assessment in Software Engineering (EASE 2021).*

```
@incollection{williams2021blogcredibilitycorpus,
  title={Towards a corpus for credibility assessment in software practitioner blog articles},
  author={Williams, Ashley, Shardlow, Matthew and Rainer, Austen},
  booktitle={Proceedings of the Evaluation and Assessment on Software Engineering},
  pages={},
  year={2021},
  publisher={ACM},
  address={New York, NY, USA}
}
```


