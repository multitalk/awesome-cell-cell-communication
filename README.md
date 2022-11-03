# Cell-cell communication

[![dockerhub-container](https://img.shields.io/badge/dockerhub-container-yellowgreen?logo=docker)](https://hub.docker.com/repository/docker/shaoxin0801/cell-cell-communication) [![jupyter](https://img.shields.io/badge/Computational--tools-cell--cell%20communication-yellow?logo=jupyter)](https://github.com/shaoxin0801/Cell-cell-communication/tree/main/method)

Collection of computational tools for [cell-cell communication inference for single-cell](https://pubmed.ncbi.nlm.nih.gov/32435978/) and spatially resolved omics, including epigenomics, transcriptomics, proteomics, metabolomics, etc. Welcome contribution. Please folk this repository and create a pull request if you have an update. Please Cite us by "Shao, X. and Fan, X. Collection of computational tools for cell-cell communication inference for single-cell and spatially resolved omics (2022)".

<img src='https://github.com/shaoxin0801/Cell-cell-communication/blob/main/img/Cell-cell%20communication.png'>

### Computational tools based on single-cell transcriptomic data
- __[CellChat](https://github.com/sqjin/CellChat)__ -[R]- CellChat enables inference and analysis of cell-cell communication for systematically detecting dysregulated cell-cell communication across biological conditions.
- __[celltalker](https://github.com/arc85/celltalker)__ -[R]- celltalker can infer putative ligand and receptor interactions from single-cell RNAseq data
- __[CellCall](https://github.com/ShellyCoder/cellcall)__ -[R]- CellCall integrates paired ligand-receptor and transcription factor activities for cell-cell communication inference.
- __[cell2cell](https://github.com/earmingol/cell2cell)__ -[python]- cell2cell is a user-friendly tool to infer cell-cell interactions and communication from gene expression of interacting proteins.
- __[RSoptSC](https://github.com/mkarikom/RSoptSC)__ -[R]- RSoptSC enables cell-cell communication and lineage inference for scRNA-seq data.
- __[scriabin](https://github.com/BlishLab/scriabin)__ -[R]- scriabin aims to provide a comprehensive view of cell-cell communication at the single-cell level without requiring subsampling or aggregation.
- __[CytoTalk](https://github.com/tanlabcode/CytoTalk)__ -[R]- CytoTalk algorithm is for de novo construction of a signaling network between two cell types using single-cell transcriptomics data.
- __[CellPhoneDB](https://github.com/Teichlab/cellphonedb)__ -[python]- CellPhoneDB is a publicly available repository of curated receptors, ligands and their interactions.
- __[NicheNet](https://github.com/saeyslab/nichenetr)__ -[R]- NicheNet can study intercellular communication from a computational perspective. NicheNet uses human or mouse gene expression data of interacting cells as input and combines this with a prior model that integrates existing knowledge on ligand-to-target signaling paths.
- __[SingleCellSignalR](https://github.com/SCA-IRCM/SingleCellSignalR)__ -[R]- SingleCellSignalR is a R package to study Cell Signaling Using Single Cell RNAseq Data.
- __[CCCExplorer](https://github.com/methodistsmab/CCCExplorer)__ -[Java]- CCCExplorer is a java-based software that predicts and visualizes the gene signaling network to aid research on crosstalk identification in the tumor microenvironment. 
- __[scMLnet](https://github.com/SunXQlab/scMLnet)__ -[R/python]- scMLnet is an R package developed to construct inter-/intracellular multilayer singaling network based on single-cell RNA-seq expression data.
- __[scTensor](https://github.com/rikenbit/scTensor)__ -[R]- scTensor is a R package for detection of cell-cell interaction using Non-negative Tensor Decomposition.
- __[COMUNET](https://github.com/ScialdoneLab/COMUNET)__ -[R]- COMUNET uses multiplex networks to represent and cluster all potential communication pathways between cell types.
- __[iCELLNET](https://github.com/soumelis-lab/ICELLNET)__ -[R]- iCELLNET enables dissection of intercellular communication using the transcriptome-based framework.
- __[iTALK](https://github.com/soumelis-lab/ICELLNET)__ -[R]- iTALK is an R toolkit for characterizing and illustrating intercellular communication.
- __[NATMI](https://github.com/forrest-lab/NATMI)__ -[python]- NATMI (Network Analysis Toolkit for Multicellular Interactions) is a Python-based toolkit for multi-cellular communication network construction and network analysis of multispecies single-cell and bulk gene expression and proteomic data.
- __[PyMINEr](https://bitbucket.org/scottyler892/pyminer_release/src/master/)__ -[python]- PyMINEr can fully automate cell type identification, cell type-specific pathway analyses, graph theory-based analysis of gene regulation, and detection of autocrine-paracrine signaling networks in silico.
- __[mistyR](https://saezlab.github.io/mistyR/)__ -[R]- mistyR facilitates an in-depth understanding of marker interactions by profiling the intra- and intercellular relationships.

### Computational tools based on spatially resolved transcriptomic data
- __[SpaTalk](https://github.com/ZJUFabLab/SpaTalk)__ -[R]- SpaTalk is a spatially resolved cell-cell communication inference method relying on the graph network and knowledge graph to model ligand-receptor-target signaling network for either single-cell or spot-based spatially resolved transcriptomic data, e.g., STARmap, MERFISH, seqFISH, Slide-seq, 10X Visium.
- __[SpaOTsc](https://github.com/zcang/SpaOTsc)__ -[python]- SpaOTsc can infer space-constrained cell-cell communications, infer spatial distance for intercellular signaling, and construct a spatial map of intercellular gene-gene regulatory information flow.
- __[Giotto](https://github.com/drieslab/Giotto)__ -[R]- Giotto introduces a two-way comparison method to identify interaction changed genes by comparing the gene expression pattern between subsets of cells within the same cell type but surrounded by different neighboring cells.
- __[CellPhoneDB](https://github.com/ventolab/CellphoneDB)__ -[python]- CellPhoneDB allows the incorporation of spatial information of the cells to define possible pairs of interacting cells (i.e. pairs of clusters sharing/coexisting in a microenvironment).
- __[CCPLS](https://github.com/bioinfo-tsukuba/CCPLS)__ -[R]- CCPLS (Cell-Cell communications analysis by Partial Least Square regression modeling) is a statistical framework for identifying cell-cell communications as the effects of multiple neighboring cell types on cell-to-cell expression variability of HVGs, based on the spatial transcriptome data.
- __[ncem](https://github.com/theislab/ncem)__ -[python]- ncem can learn cell communication from spatial graphs of cells.
- __[GCNG](https://github.com/xiaoyeye/GCNG)__ -[python]- GCNG uses graph convolutional neural network and spaital transcriptomics data to infer cell-cell interactions.
- __[SCVA](https://github.com/damienArnol/svca)__ -[R/python]- SCVA enables quantifying different dimensions of spatial variation and in particular quantifies the effect of cell-cell interactions on gene expression.
