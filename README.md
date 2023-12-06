# Create_fasta_file
A code script to generate a fasta file by combining multiple sequence fragments and 
filtering out unwanted characters usually seen in Clustal omega outputs.

####
The consensus sequence function creates a consensus sequence from a list of aligned 
sequences by finding the most common character at each position in the alignment (retaining
gaps as represented by dashes) and concatenating these characters into a single consensus sequence.
