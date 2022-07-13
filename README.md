# S288_gRNA_Design
Designing gRNAs for Cpf1 and Cas9 across the entire S. cerevisiae S288C genome

gRNA sequences were based on the S288C reference genome - S288C_reference_sequence_R64-2-1_20150113.fsa (from the Saccharomyces Genome Database). 
Download link: http://sgd-archive.yeastgenome.org/sequence/S288C_reference/genome_releases/S288C_reference_genome_R64-1-1_20110203.tgz

For Cas9 guides, the 20 base pairs (bp) immediately preceding the NGG PAM sequence was considered the target sequence. 
For Cpf1 guides, the 23 base pairs immediately following the TTTV PAM sequence was considered the target. 

Target sequences were found on both strands for each chromosome. 

Any guides that shared the same target sequence were removed to yield 557711 Cpf1 guides and 873424 Cas9 guides. 

Appropriate homology arms for Gibson cloning were then added to each gRNA sequence. 
