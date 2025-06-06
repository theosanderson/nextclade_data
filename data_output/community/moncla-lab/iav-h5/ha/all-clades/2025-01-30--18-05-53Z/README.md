# A(H5) all-clades dataset with A/Goose/Guangdong/1/96 reference

| attribute            | value                                    |
| -------------------- | ---------------------------------------- |
| dataset name         | A(H5) all-clades (provisional)          |
| reference strain     | A/Goose/Guangdong/1/96(H5N1)             |
| reference accession  | AF144305.1                               |

## Authors and contacts

Maintained by: [Jordan Ort](https://lmoncla.github.io/monclalab/team/JordanOrt/)

With the help of: [Louise Moncla](https://lmoncla.github.io/monclalab/team/LouiseMoncla/), Samuel Shephard, Sonja Zolonski, Tommy Lam, Todd Davis, and Richard Neher

## Reference

See [Ort et al. (preprint)](https://doi.org/10.1101/2025.01.07.631789) for more details on the development of this dataset. If you use these A(H5) Nextclade datasets, please cite: Ort, J. T., Shepard, S. S., Zolnoski, S. A., Lam, T. T.-Y., Davis, T., Neher, R., & Moncla, L. H. (2025). Development of avian influenza A(H5) virus datasets for Nextclade enables rapid and accurate clade assignment. bioRxiv, https://doi.org/10.1101/2025.01.07.631789.

## Scope of this dataset

This dataset uses the first highly pathogenic avian influenza (HPAI) isolate (A/Goose/Guangdong/1/96) as a reference and is suitable for the analysis of circulating and historical A(H5) sequences, including low pathogenici avian influenza (LPAI) isolates.

## Features

This dataset supports

 * Assignment to clades and subclades based on the provisional nomenclature defined by the FAO/WHO/WOAH H5 Nomenclature Working Group
 * Sequence quality control (QC)
 * Phylogenetic placement
 * Annotations for glycosylation sties, HA cleavage site sequence, and presence/absence of a polybasic cleavage site

## Clades of A(H5) avian influenza viruses

The FAO/WHO/WOAH H5 Nomenclature Working Group define "clades" as genetically divergent groups of viruses, based on their HA gene segment.
Viruses falling into a given clade share a common ancestor with significant bootstrap support and have low levels of within-clade diversity.
When significant within-clade diversity is seen, these clades can be further split into sub-clades; for example, clade `2.3.4.4` is being split into eight additional sub-clades, named `2.3.4.4a` through `2.3.4.4h` due to high circulating diversity within the clade.
This Nextclade dataset incorporates these provisional `2.3.4.4` sub-clades, as well as sub-clades `2.3.2.1a` through `2.3.2.1g` for the `2.3.2.1` split.

## Alternative, and complementary approaches for A(H5) clade assignment

Two additional tools exist for assigning clades to A(H5) viruses, which also accommodate the recent `2.3.2.1` and `2.3.4.4` clade splits.

1. [LABEL](https://wonder.cdc.gov/amd/flu/label/): this command-line tool is built and maintained by Sam Shepard, and performs clade assignment for all current `2.3.2.1` and `2.3.4.4` clade splits.
2. [BVBRC Subspecies Classification Tool](https://www.bv-brc.org/app/SubspeciesClassification): this is a drag and drop tool that classifies a variety of viruses, including influenza A H1N1, H3N2, and H5N1.

The clade assignments in this Nextclade dataset were validated against LABEL assignments and shown to be generally well-matched across subclades. The figure below shows a direct comparison of assignments for 19,833 HA sequences from GISAID, performed using LABEL and this NextClade dataset for all A(H5) clades. Note that the results for clades `2.3.2.1`, `2.3.4.4`, and their subclades are not shown in this figure.

![Figure 1: Comparison between LABEL and Nextclade for all-clade assignments](https://raw.githubusercontent.com/moncla-lab/h5-nextclade/refs/heads/main/figures-for-dataset-readmes/all-clades.svg)

## What is Nextclade dataset

Read more about Nextclade datasets in Nextclade documentation: https://docs.nextstrain.org/projects/nextclade/en/stable/user/datasets.html