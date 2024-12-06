# SpaLLM
--------------
我们建立类似于下面的GitHub项目：

- [ADGC: Awesome Deep Graph Clustering](https://github.com/yueliu1999/Awesome-Deep-Graph-Clustering)


- [Deep Clustering](https://github.com/zhoushengisnoob/DeepClustering)

--------------
## 基于transformer架构的单细胞大模型

## 什么是单细胞大模型？

介绍：

单细胞大模型（Single-Cell Large Models）是指用于处理单细胞数据的深度学习模型，特别是那些具有复杂结构、庞大参数空间和较高计算需求的模型。这些模型通常用于从单细胞RNA测序（scRNA-seq）数据中提取细胞层次上的信息，帮助研究者更好地理解细胞间的异质性、基因表达模式以及细胞的功能状态。

单细胞大模型的核心特点包括：

- 高维数据处理：单细胞数据通常是高维的，每个细胞包含成千上万的基因表达信息。传统的机器学习方法可能难以处理这种数据的复杂性，而大模型则能够通过层次化的深度学习网络来处理这些高维信息。

- 数据融合能力：单细胞数据不仅仅是基因表达，还包括空间位置信息、细胞间的相互作用以及其他的“多模态”数据。单细胞大模型能够同时处理这些不同类型的数据，从而获得更全面的分析结果。

- 增强的泛化能力：由于大模型有更多的参数和更复杂的结构，它们能够捕捉到单细胞数据中的深层次模式，提高模型的泛化能力，即能够更好地适应不同数据集的变化。

- 迁移学习：在单细胞分析中，数据集可能较小，但通过大模型的迁移学习方法，可以利用其他相关领域的大规模数据集进行预训练，从而弥补小样本问题。

- 提高预测精度：通过使用深度学习中的先进技术（例如自注意力机制、图神经网络等），单细胞大模型能够显著提高基因表达预测、细胞类型分类和空间定位等任务的精度。

典型的单细胞大模型包括基于Transformer架构的模型、图神经网络（GNN）以及自监督学习方法等。这些模型不仅限于基因表达的分析，也可能涉及到细胞发育、疾病机制的探索等方向。

总的来说，单细胞大模型正逐步成为单细胞转录组学分析的一个重要工具，它们有助于深度挖掘单细胞数据中的复杂信息，为精准医学、细胞生物学等领域提供更多的洞察。



## Important Survey Papers

| Year | Title                                                        |    Venue    |                            Paper                             | Code |
| ---- | ------------------------------------------------------------ | :---------: | :----------------------------------------------------------: | :--: |
| 2024 | **Transformers in single-cell omics: a review and new perspectives** |    Nature Methods   | [Link](https://doi.org/10.1038/s41592-024-02353-) |  - |





## Papers of single cell model
| Year | Title                                                        |  Venue  |                            Paper                             |                             Code                             |
| ---- | ------------------------------------------------------------ | :-----: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| 2024 | **Large-scale foundation model on single-cell transcriptomics** |   Nature Methods    | [Link](https://doi.org/10.1038/s41592-024-02305-7) |         [Link](https://github.com/biomap-research/scFoundation)                              |
| 2024 | **scGPT: toward building a foundation model for single-cell multi-omics using generative AI** |   Nature Methods    | [Link](https://doi.org/10.1038/s41592-024-02201-0) |    [Link](https://github.com/bowang-lab/scGPT)                            |
| 2023 | **scBERT as a large-scale pretrained deep language model for cell type annotation of single-cell RNA-seq data**              |  nature machine intelligence   |          [Link](https://doi.org/10.1038/s42256-022-00534-z)            |         [Link](https://github.com/TencentAILabHealthcare/scBERT)       



## Papers of spatial Transcriptomics model
| Year | Title                                                        |  Venue  |                            Paper                             |                             Code                             |
| ---- | ------------------------------------------------------------ | :-----: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| 2023 | **Transfer learning enables predictions in network biology** |   Nature    | [Link](https://doi.org/10.1038/s41586-023-06139-9) |         [Link](https://huggingface.co/ctheodoris/Geneformer)   |


