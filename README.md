# Bulk RNA-seq Assignment

This assignment was completed as part of the *Comparative and Regulatory Genomics* course in the Master of Bioinformatics program at KU Leuven.

## Overview

In this project, I performed a bulk RNA-seq analysis by reproducing an experiment from a published paper, but using only a subset of the original dataset. The goal of the assignment was to learn and apply standard RNA-seq data processing and analysis techniques, including:

* Preprocessing and quality control
* Alignment and quantification
* Differential gene expression analysis
* Functional enrichment analysis

This study investigates how regular exercise suppresses liver cancer in mice by analyzing gene expression changes. It compares exercised and non-exercised mice in both healthy and tumorous liver tissues to uncover differently expressed genes.

## Dataset

All processed data can be found here:

https://www.ncbi.nlm.nih.gov/Traces/study/?acc=PRJNA1142455&o=acc_s%3Aa

Paper can be found here: 

https://onlinelibrary.wiley.com/doi/full/10.1111/gtc.13161

## Tools & Packages Used

The following tools and packages were used throughout the analysis:

* **FastQC**: For quality control of FASTQ files.
* **STAR**: For read alignment to the reference genome.
* **samtools**: For processing and sorting BAM files.
* **sra-tools**: For downloading FASTQ files from the Sequence Read Archive (SRA).
* **subread**: For gene quantification using featureCounts.
* **R** (version 3.6.3 or compatible): Base environment for statistical analysis.
* **DESeq2**: R package for differential expression analysis.
* **pheatmap**: R package for heatmap visualization.
* **ClusterProfiler**: R package for functional enrichment analysis.
* **ggplot2**: R package for data visualization.
* **RColorBrewer**: R package for color palettes, used with pheatmap.

## Analysis

The Jupiter notebooks used for the analysis can be found in the notebooks folder!