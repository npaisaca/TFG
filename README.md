# RNA-seq and differential gene expression for transcriptomic analysis - TFG 23/24

### Overview

Bioinformatic analysis of the transcriptomes of females, males and neomales of the European sea bass (*Dicentrarchus labrax*). RNA extracted from gonadal tissue was sequenced with NGS methods; this repository includes the code files devised for the appropriate manipulation and preparation of the reads through an RNA-seq, the PCA and differential expression analysis, and the Gene Ontology enrichment study to classify the resulting DEGs.

The contents of this repository and the results of the analysis were included in my TFG (2023-2024).

### Files

- **RNAseq_analysis_def**: includes the code for the different softwares of the RNA-seq, from the obtention of the reads file to the generation of the counts file.
- **DESeq_analysis_def**: PCA and differential expression analysis.
- **GO_and_pathway_analysis_def**: GO terms enrichment analysis (g:Profiler), generation of overview plots and dataframes.
- **graphs_def**: includes the code for the graphing of the Volcanoplots, the GO enrichment scatterplot with the KEGG pathways, and other graphs that due to space or redundancy were not added to the final TFG report.

All files were created in an R-markdown format.
