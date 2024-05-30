#t-distributed Stochastic Neighbor Embedding (t-SNE)

It is a tool to visualize high-dimensional data. It converts similarities between data points to joint probabilities and tries to minimize the distance between low-dimensional embedding and the high-dimensional data. t-SNE tries to keep neighborhood point as close as possible and non-neighborhood point as far away from possible. Used for dimensionality reduction applications (unsupervised learning).

Two most important parameters of T-SNE:

Perplexity: Number of points whose distances you want to preserve in a low dimensional space.
Step size: number of iterations. At every iteration, the algorithm tries to reach a better solution.
Note: When the value of perplexity is small, suppose 3, then only 3 neighborhood point distance is preserved in a low dimensional space. For a stable result, you must choose multiple perplexity values where perplexity is less than the number of data points and also run the algorithm for longer times.

Website: https://distill.pub/2016/misread-tsne/


MNIST dataset can be downloaded from Kaggle : 
https://www.kaggle.com/c/digit-recognizer/data
