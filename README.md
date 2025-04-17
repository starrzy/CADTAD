# Cancer Driver Topologically Associated Domains identify oncogenic and tumor suppressive lncRNAs
CADTAD is a pipeline to identify potential cancer driver lncRNAs in silico.


## Pre-requisite
```
conda env create -f env.yaml
```

## Introduction
Cancer long noncoding RNAs (lncRNAs) have been identified by experimental and in silico methods. However, current approaches for mining cancer lncRNAs are not sufficient and effective. To uncover them, we focused on the core cancer driver lncRNAs, which directly interact with cancer driver protein-coding genes (PCGs). We investigated various aspects of cancer lncRNAs, including their genomic locations, expression patterns, and direct interactions with cancer driver PCGs to explore the characteristics of cancer lncRNAs, and developed a pipeline to unearth conserved candidate cancer driver lncRNAs. Finally, we validated the reliability of potential cancer driver lncRNAs through functional analysis of bioinformatics data and CRISPR-Cas9 knockout experiments. We found that most cancer lncRNAs were located in cancer driver topologically associated domains (CDTs). Moreover, some cancer lncRNAs showed a high tendency toward co-expression and binding sites with cancer driver PCGs. Utilizing these distinctive characteristics, we developed a pipeline CADTAD to unearth conserved candidate cancer driver lncRNAs in pan-cancer, including 256 oncogenic lncRNAs, 177 tumor suppressive lncRNAs, and 75 dual-function lncRNAs, as well as in three individual cancer types, and validated their cancer-related characteristics. More importantly, the function of 10 putative cancer driver lncRNAs in prostate cancer was subsequently validated to influence cancer phenotype through cell studies. In light of these findings, our study offers a new perspective from the 3D genome to study the roles of lncRNAs in cancer. Furthermore, we provide a valuable set of potential lncRNAs that could deepen our understanding of the oncogenic mechanism of cancer driver lncRNAs.

## Citation
Rao Z#, Zhang M#, Huang S, Wu C, Zhou Y, Zhang W, Lin X, Zhao D. CADTAD: CAncer Driver Topologically Associated Domains identify oncogenic and tumor suppressive lncRNAs. bioRxiv. doi: https://doi.org/10.1101/2024.03.19.585685

## Contact Information
More information please contact Ziyan Rao at raoziyan@pku.edu.cn
