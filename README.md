# PAC1 — Anàlisi de dades òmiques  
**Autor:** Ricard Gonzalez  
**Màster Universitari en Bioinformàtica i Bioestadística**  
**Universitat Oberta de Catalunya**  
**Març de 2025**

## Descripció general

Aquest repositori conté el material associat a la realització de la PAC1 de l’assignatura *Anàlisi de dades òmiques*.
Tots els materials necessaris per reproduïr la PAC1 es poden trobar en aquest repositori.

## Contingut del repositori

| Fitxer | Descripció |
|--------|------------|
| `ricard_gonzalez_PAC1_ADO.qmd` | Informe en format Quarto, amb codi R integrat |
| `ricard_gonzalez_PAC1_ADO.pdf` | Versió PDF final de l’informe (generada a partir del `.qmd`) |
| `human_cachexia.csv` | Fitxer de dades original, un conjunt de dades metabolòmic |
| `metadades.md` | Fitxer amb descripció del conjunt de dades original |
| `cachexia_summarizedExperiment.Rda` | Objecte `SummarizedExperiment` generat a partir de les dades, en format binari |
| `custom.tex` | Fitxer LaTeX amb configuració d’estil altres aspectes personalitzats |
| `references.bib` | Fitxer BibTeX amb les referències bibliogràfiques emprades |
| `elsevier-vancouver-short-author-list.csl` | Arxiu d'estil CSL per a la generació del format Vancouver |
| `ricard_gonzalez_PAC1_ADO_files/` | Directori auxiliar generat per Quarto (per a figures) |
| `.gitignore` | Fitxer per excloure elements del control de versions |

## Reproducció del projecte

Per reproduïr el contingut de l’informe, cal disposar d’un entorn R amb els següents paquets instal·lats:

- `data.table`
- `Biobase`
- `SummarizedExperiment`
- `ggplot2`
- `kableExtra`
- `showtext`

L'autor recomana treballar dins l'entorn de desenvolupament **RStudio**, utilitzant el fitxer de projecte `PAC1-omics-RGR.Rproj`. Un cop instal·lats els paquets, es pot generar el PDF mitjançant el botó “Render” de Quarto.
Es poden verificar les versions dels paquets utilitzats dins l'informe en format PDF.
