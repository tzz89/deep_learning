## Factorization Machine
It is supervised learning method usually applied on categorical data to learn the embeddings of the categorical features. 
The algorithm takes the pairwise dot product between each feature (embeddings) to capture the relationship between each feature.

### References
1. https://www.ismll.uni-hildesheim.de/pub/pdfs/Rendle2010FM.pdf (Paper on Factorization Machine)
2. https://arxiv.org/abs/1703.04247 (Paper on DeepFM) 
3. https://www.youtube.com/watch?v=7ubk_YXPRbA&list=PLQHzlagV3jqJ90GRAeqmfxepiHJm5ge4x&index=2 (Tutorial on Factorization Machine)
4. https://medium.com/@datadote/factorization-machines-pictures-code-pytorch-9fca1c300838 (Factorization machine on pytorch)


### Advantage of FM
1. It is relative cheap to compute O(n*k) where n is number of feature and k is the embedding size


### Use Cases
1. Recommendation Systems