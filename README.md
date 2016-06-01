# tRNAscan-SE

[tRNAscan-SE](http://lowelab.ucsc.edu/tRNAscan-SE) is a program for improved transfer RNA detection in genomic sequence.

This project encapsulated tRNAscan-SE into a docker container.

## Usage
```usage
docker run \
    -v data_dir_path:/data \
    yookuda/trnascan_se \
    tRNAscan-SE \
        [-options] \
        /data/input_fasta_file
```
