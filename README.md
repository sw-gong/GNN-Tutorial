### Graph Neural Network Tutorial for Deep Learning (CO460)

#### 1. Pytorch Geometric Framework
- Understanding Message Passing Scheme in Pytorch Geometric.
- Efficient graph data representations and paralleling minibatching graphs.
- Showcase the implementation of **Graph Convolution Networks** (Kipf & Welling, [SEMI-SUPERVISED CLASSIFICATION WITH GRAPH CONVOLUTIONAL NETWORKS](https://arxiv.org/abs/1609.02907), ICLR 2017), and you should implement **GraphSAGE** (Hamilton et al, [Inductive Representation Learning on Large Graphs](https://arxiv.org/abs/1706.02216), NIPS 2017) in the lab based on message passing scheme.

#### 2. Vertex Classification
- Showcase a model developed based on our GCN implementation to do vertex classification on Cora dataset.
- Develop a model with **your own** GraphSAGE (with mean/sum/max aggregation) implementation on the same dataset to get insights of difference.

#### 3. Graph Classification
- Implement **GINConv** (Xu et al, [HOW POWERFUL ARE GRAPH NEURAL NETWORKS?](https://arxiv.org/abs/1810.00826), ICLR 2019) on graph classification benchmark dataset (IMDB) and compare different aggregation functions (SUM/MEAN/MAX).


#### Acknowledgments
This tutorial is designed based the [Pytorch Geometric](https://github.com/rusty1s/pytorch_geometric) library, and we own many thanks to Matthias Fey for making this great library to facilitate the research in Graph Neural Networks. 
