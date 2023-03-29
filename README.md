# sequence-filteration
This python script uses Biopython libraries along with Pandas to filter the required sequences from a large file. If you have a FASTA file that contains a huge bunch of sequences and you need to pick selected ones then you need this script to easily filter the required sequences. 
Follow these steps along with this script to successfully filter specified sequences from a large sequence set. 
Make a .xlsx file containing the accession numbers of required sequences. 
Note: if accession numbers are in QQ122345.1 format then remove ".1" using excel data delimited mode. 
Also, check the FASTA file has a separate accession number starting with ">" and has a space at the end just before "|".  
You can replace ".1" with empty " " using find and replace option from Notepad++
Now use this file in this script to filter required sequences 
