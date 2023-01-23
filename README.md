# Transformers as Graph Neural Networks;
## Or: Graph Neural Networks as Transformers
### Or: How I learned to stop worrying and love the attention mechanism regardless of tensor representation

This repository exists to explore the operations used in the vanilla Transformer self-attention mechanism, how they can be represented as graph operations, and how the performance compares for point clouds of O(100k) nodes/points. 

1. Start with [Transformer vs GNN](0-Transformer_vs_GNN_Annotated.ipynb) to prove to yourself that the Transformer self-attention can be equivalently calculated with sparse graph-like operations.
2. Then, [Performance Comparison](2-PerformanceComparison.ipynb) explores the various ways to implement the Transformer self-attention mechanism, and compares the performance of the different implementations.