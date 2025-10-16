# HpGP_ICE_Quast

## Overview
This repository summarizes the comparative assembly quality assessment of *Helicobacter pylori* genomic sequences (**HpGP**) using **QUAST**.  
The goal of this analysis is to evaluate genome fraction among *H. pylori* strains from different geographic origins, using published representative reference genomes from **Europe**, **East Asia**, and **Africa2**.

---

## Reference Genomes and Comparative Results

### 1. *Hp 26695* (Europe)
Using the European reference genome *Hp 26695*, high genome alignment quality was observed mainly among European-origin strains.  
Strains from other regions exhibited substantially lower genome fractions, indicating clear sequence divergence from the European lineage.

### 2. *F16* (East Asia)
With the East Asian reference *F16*, only strains from East Asia (Japan, China, Korea, Singapore) achieved **>90% genome fraction**, reflecting strong sequence conservation within the East Asian cluster.  

### 3. *SouthAfrica20* (Africa2)
Using the African reference *SouthAfrica20*, only four strains — **HpGP-ZAF-001**, **HpGP-ZAF-006**, **HpGP-ZAF-007**, and **HpGP-ZAF-009** — reached **>80% genome fraction**.  
This finding indicates that the Africa2 lineage possess region-specific structures distinct from other populations.

---

## Conclusion
Comparative analyses with QUAST demonstrate clear **geographic clustering and sequence divergence** across *H. pylori* populations from Europe, East Asia, and Africa.  
These results highlight the **regional adaptation and evolutionary differentiation** of genomic sequences, reflecting the co-evolution between *H. pylori* and its human host populations.

---

## Methods
- **Tool:** QUAST (Quality Assessment Tool for Genome Assemblies)  
- **Input:** *De novo* assembled, circular, complete genomic sequences from 1012 *H. pylori* genomes  
- **References:**  
  - *Hp 26695* (Europe)  
  - *F16* (East Asia)  
  - *SouthAfrica20* (Africa2)  
- **Metric Reported:** % Genome fraction aligned to each reference genome  

---

## Reference Genomes and Publications

### F16
- **Publication:** Mikihiko Kawai *et al.*  
  *Evolution in an oncogenic bacterial species with extreme genome plasticity: Helicobacter pylori East Asian genomes*  
  *BMC Microbiology* **11**, Article 104 (2011)  
- **Database:** GenBank (F16 strain sequence deposited)

---

### SouthAfrica20
- **Publication:** Stacy S. Duncan *et al.*  
  *Genome Sequences of Three hpAfrica2 Strains of Helicobacter pylori*  
  *Genome Announcements* **1**(5): e00729-13 (2013)  
  DOI: [10.1128/genomeA.00729-13](https://doi.org/10.1128/genomeA.00729-13)  
- **Database:** GenBank (SouthAfrica20 strain sequence deposited)

---

### H. pylori 26695
- **Publication:** Tomb F. *et al.*  
  *The complete genome sequence of the gastric pathogen Helicobacter pylori*  
  *Nature* **388**, 539–547 (1997)  
- **Database:** GenBank (26695 strain sequence deposited)

---

### H. pylori Genome Project (HpGP)
- **Publication:** Kaisa Thorell *et al.*  
  *The Helicobacter pylori Genome Project: insights into H. pylori population structure from analysis of a worldwide collection of complete genomes*  
  *Nature Communications* **14**, 8184 (2023)
- **Database:** GenBank (1012 HpGP sequence deposited)

---

## Citation
If you use this dataset or analysis summary, please cite:
- Andrés Julián Gutiérrez-Escobar *et al.*
*Global diversity of integrating conjugative elements (ICEs) in Helicobacter pylori and their influence on genome architecture* (2025)


