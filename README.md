# Assignment-1
Primer Design for B2M Gene - NGS Assignment
## Student Information
- **Name:** Shreya Sharma
- **Date:** January 11, 2026
- **Course:** Next-Generation Sequencing Module

- # Part 1: Gene Selection
From the provided list of 10 housekeeping genes, I selected:
- **Gene:** B2M (Beta-2-microglobulin)
- **Function:** Component of MHC class I molecules
- **NCBI mRNA Accession:** NM_004048.4

- # Part 2: Primer Design Parameters
- ### NCBI Primer-BLAST Settings Used:
- PCR Product Size- 80-200 bp 
- Primer Tm Range- 57-63°C (Optimum 60°C)
- Primer GC Content- 40-60%
- Exon-Exon Junction- Required
- Specificity Database- Human genome (taxid:9606)
<img width="1891" height="901" alt="primer-settings png" src="https://github.com/user-attachments/assets/21d0cbe1-3c98-4070-990c-41baa02f02cb" />
<img width="1613" height="937" alt="primer-settings png 1" src="https://github.com/user-attachments/assets/fc21d2d8-3020-4f5e-9b05-247ddae649d2" />

- # Part 3: Selected Primer Pair
# Primer Pair 1 Details:
- Sequence (5'→3') - Tm, GC%, Length
- **Forward Primer** - `GCCCAGATAGTTAAGTGGGATCG` 61.04°C, 50.00%, 24 bp
- **Reverse Primer** - `ATTCATCCAATCCAAATGCGGC` 60.22°C, 45.45%, 22 bp
# Primer Properties:
- **Product Size:** 80 bp (within 80-200 bp requirement)
- **Exon-Exon Junction:** Spans exon boundary 376/377
- **Self-Complementarity:** Low scores (4.0, 3.0) - minimal primer-dimer risk
<img width="1794" height="911" alt="primer-blast-results 1" src="https://github.com/user-attachments/assets/4d54d731-70db-4955-aa57-5d52ddd66ede" />
<img width="1821" height="933" alt="primer-blast-results" src="https://github.com/user-attachments/assets/1aa7dee4-522e-4401-946d-c7a22b648677" />
<img width="1725" height="431" alt="primer-blast-results 2" src="https://github.com/user-attachments/assets/9c10e977-de90-4635-8767-005034ed17dc" />

- # Part 4: Specificity Check
- ## How I Performed Specificity Check:
1. I've Used "BLAST to Genome" function in Primer-BLAST results
2. Searched against: **Human genome (GRCh38.p14 reference assembly)**
3. Parameters: Megablast for highly similar sequences
# Specificity Results:
**BLAST Search Results for 80 bp Product:**
<img width="1518" height="871" alt="blast-results (3)" src="https://github.com/user-attachments/assets/b3a99ed8-af63-4802-b931-bc91b5f533b8" />
# Specificity Analysis:
- Both alignments are to Chromosome 15 - where B2M gene is located
- No alignments to other chromosomes - confirms specificity
- 63.9% identity indicates mismatches (due to introns in genomic DNA)
- E-value 1e-08 indicates significant match

# End
