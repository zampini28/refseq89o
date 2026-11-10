# refseq89o — MITOS2 reference data (RefSeq 89 Opisthokonta (Metazoa + Fungi))

A mirror of `refseq89o.tar.bz2` from the MITOS2 reference data, Zenodo record
[4284483](https://zenodo.org/records/4284483) (doi:[10.5281/zenodo.4284483](https://doi.org/10.5281/zenodo.4284483)),
byte for byte (md5 `6e6ce66843f5ad33758af174bfa128e7`, the same as Zenodo's). It is mirrored here only because Zenodo throttles
downloads; MitOmics downloads it from this repository and falls back to Zenodo.

    wget https://raw.githubusercontent.com/zampini28/refseq89o/refs/heads/main/refseq89o.tar.bz2
    echo "6e6ce66843f5ad33758af174bfa128e7  refseq89o.tar.bz2" | md5sum -c -
    tar xjf refseq89o.tar.bz2          # -> refseq89o/, used as: runmitos ... -r refseq89o -R .

**Authors:** Matthias Bernt, Frank Jühling, Alexander Donath, Abdullah H. Sahyoun, Manja Marz,
Peter F. Stadler, Martin Middendorf. *Reference data for MITOS2.* Zenodo (2020).

**License:** [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by-4.0/),
as published on Zenodo. Unmodified.
