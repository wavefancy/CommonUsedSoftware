## Common used genetic softwares
### Genetic relationship by king
  [`plink2 --make-king-table`](https://www.cog-genomics.org/plink/2.0/distance#make_king) or [KING software](http://people.virginia.edu/~wc9c/KING/manual.html),
  **Genome-wide SNPs are required in KING**. Please do not prune or filter any "good" SNPs that pass QC prior to any KING 
  inference, unless the number of variants is too many to fit the computer memory,
  e.g., > 100,000,000 as in a WGS study, in which case rare variants can be filtered out. 
  LD pruning is not recommended in KING.
  
  Inference cut-off, [Paper here](https://academic.oup.com/bioinformatics/article/26/22/2867/228512):
  - MZT > 0.35
  - PO, FULL sib > 0.17
  - 2nd Degree > 0.088
  - 3nd Degree > 0.044
  
  
 
