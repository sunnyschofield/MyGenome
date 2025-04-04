# MyGenome
ABT480 Project
Sequence Quality Assessment

## Files
UFVPY94_1.fq.gz (sequence file in the forward direction)
UFVPY94_2.fq.gz (sequence file in the reverse direction)

## Programs
FastQC
Trimmomatic
Velvet

## Module 1 NCBI Entry
[Link to NCBI]([url](https://www.ncbi.nlm.nih.gov/))
Sample Name: UFVPY94
Organism: Pyricularia orzyae
Host: Melinis repens
Collection Date: 2018
Location: MG, Brazil
BioSample ID: SAMN47133007
SRA Accession Number: SRR32520114

## Module 2 Genome Quality Assessment
*You will need FastQC and Trimmomatic downloaded*
I have two files: UFVPY94_1.fq.gz and UFVPY94_2.fq.gz
Two sequence files, one in the forward direction and one in the reverse.
Make a MyGenome directory (referred to from now on as `MyGenomeDir`).
Move the two sequences files into `MyGenomeDir`.
Unix Commands
```
user:~/MyGenomeDir/$ fastqc UFVPY94_?
```


## Module 3 Trimming Genome
Unix

## Module 4 Trimmed Genome Quality Assessment
Unix
**Final Genome Size**

## Module 5 Velvet Optimizer
Unix
