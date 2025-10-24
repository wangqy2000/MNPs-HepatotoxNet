# Bioinformatics Project

This is my research project, which consists of two parts: download of homologous gene tables and WGCNA analysis.

## Code Structure

`Download_Homologous_Gene_Table.R`: Code for downloading the homologous gene tables of experimental animals to humans.

`WGCNA.R`: Code for constructing the hepatotoxicity gene network using WGCNA.
 
## Installation Guide

Before running these scripts, please make sure to install the following R packages:

- biomaRt
- WGCNA
- stringr

You can install these packages using `install.packages()`  and  `BiocManager::install()`  commands in R.

## Usage

Place the required data files in the root directory of the project.

1.Run `Download_Homologous_Gene_Table.R` for downloading the homologous gene tables of experimental animals to humans.

2.Execute `WGCNA.R` for constructing the hepatotoxicity gene network.

## Contact

For questions or further information, please contact me at (wangqy2023@lzu.edu.cn).
