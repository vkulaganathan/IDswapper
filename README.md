# IDswapper
Convert given gene IDs to various other IDs. (under development, please come back later)

**Usage**
<br>``$ IDswapper --infile test.tsv --id-column-index 0 --fetch "25" "5" "10" --outfile append_test.tsv``</br>

For large files that are gzip compressed
<br>``$ IDswapper --infile test.tsv.gz --id-column-index 0 --fetch "25" "5" "10" --outfile append_test.tsv.gz``</br>

**Fetch Table**
Please use these options for the ``--fetch `` argument
| Fetch Argument | Columns to be appended |
|---|---|
| 2 | Ensembl Transcript ID |
| 3 | Ensembl Protein ID |
| 4 | HGNC ID |
| 5 | Gene Symbol |
| 6 | Gene Description |
| 10 | Chromosome Location |
| 12 | Gene Aliases |
| 18 | Entrez Gene ID |
| 19 | Ensembl Gene ID |
| 20 | VEGA ID |
| 21 | UCSC ID |
| 23 | Refseq Accession |
| 25 | Uniprot ID |
| 30 | COSMIC Entry |
| 31 | OMIM ID |
| 36 | Orphanet ID |
| 43 | CD Name |
| 47 | RNA Central ID |
| 51 | MANE Select ID |
