Single-cell CITE-seq integration in Python
==========================================

CITE-seq is a method for cellular indexing of transcriptomes and epitopes by sequencing. CITE-seq datasets comprise transcriptome-wide measurements for single cells (gene expression) as well as surface protein level information, typically for a few dozens of proteins. The method is described in `Stoeckius et al., 2017 <https://www.nature.com/articles/nmeth.4380>`_ and also `on the cite-seq.com website <https://cite-seq.com/>`_.

These notebooks cover different CITE-seq datasets:

- `analysis of 5k peripheral blood mononuclear cells (PBMCs) <1-CITE-seq-PBMC-5k.html>`_ showcasing *dsb* normalisation and data integration with MOFA+ (data by 10x Genomics can be found `here <https://support.10xgenomics.com/single-cell-gene-expression/datasets/3.0.2/5k_pbmc_protein_v3>`_).

- `calculating weighted nearest neighbours for the 5k PBMCs dataset <2-CITE-seq-PBMC-5k-Weighted-Neighbours.ipynb>`_ that also demonstrates how to handle multiple multimodal embeddings.


.. toctree::
   :hidden:
   :maxdepth: 3

   1-CITE-seq-PBMC-5k.ipynb

