# Build the résumé

[resume.tex](../resume.tex) assembles the résumé from the section files in this directory.

With Tectonic installed, run these commands from the repository root.

```sh
mkdir -p output/pdf
tectonic --outdir output/pdf resume.tex
```

The result is [output/pdf/resume.pdf](../output/pdf/resume.pdf).
