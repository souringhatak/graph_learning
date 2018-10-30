# graph_learning
This repository contains some graph learning algorithms with the help of LSTMs and GRUs. The codes runs really fast provided a capable GPU is present.

# Instructions for getting node embeddings for a graph
1. Generate a walk sequence of the graph using any algorithm for your choice like nod2vec.
2. Save the walk sequence as 'seqs.mat' file, where a numpy matrix called 'seqs' should contain the walk sequences generated by the algorithm. For example, matrix should be in order of m x n, where n is the walk length for each node.
3. The above mentioned file should present in the same directory where this notebook is kept.
4. Simply run this notebook completely and the emb will be saved in the working directory as 'node_emb.npy'.
5. To fine-tune the model, you can tweak the epochs, batch_size etc in the code mentioned in the 'training' cell, i.e., the 4th cell from the beginning.
