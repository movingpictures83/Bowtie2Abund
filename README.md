# Bowtie2Abund
# Language: Python
# Input: TXT
# Output: TXT
# Tested with: PluMA 2.0, Python 3.6
# Dependencies: pandas==1.1.5, argparse==1.1

PluMA plugin that takes Bowtie output and converts into a TXT file of abundances.

Input is a TXT file of keyword-value pairs:
SAM: input SAM file
N_READS: number of reads
COV_CUTOFF: similarity cutoff
