# meta_programs_tirosh

The Tirosh metaprograms from <https://www.nature.com/articles/s41586-023-06130-4> contain several unapproved HGNC names. Here we catalog and fix them. You can view the table of patched names (along with the script used to patch them) [here](https://rpubs.com/matthewzatzman/mp_fix).

The file with final patched names is `tirosh_mp_patched.txt`, which has the following columns:

| Column          | Description                                                     |
|------------------|------------------------------------------------------|
| Gene            | The corrected patched HGNC gene symbol                          |
| original_symbol | The original gene symbol sourced from the excel table           |
| Approved        | Whether the `Original_Symbol` is an approved HGNC symbol or not |
| cell_type       | Celltype from which the meta-program was originally measured    |
| meta_program    | Name of the metaprogram                                         |
| gene_rank       | Rank of the gene in the original table                          |
