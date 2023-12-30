## To generate the `publication.md` file insert one of the following instructions into the terminal:

### Generate the publication.md file directly form the .bib file

```bash
pandoc -t markdown_strict --citeproc publication-bib.md -o publication.md --bibliography ref.bib
```

### Generate the publication.md file form the .tex file

```bash
pandoc -t markdown_strict --citeproc list-of-publications.tex -o publication.md --bibliography ref.bib
```
