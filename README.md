# IBM 6540 Group Project

## Project
**Analyzing the Effect of Discounts on Retail Sales Volume and Revenue Using Seasonal Retail Data**

This RStudio project contains the Quarto RevealJS proposal presentation, the retail sales dataset, and a short project summary document.

## Files

- `IBM-6540-Group-Project.Rproj` — RStudio project file
- `Group1-Proposal-Presentation.qmd` — Quarto RevealJS slide deck
- `data/Retail_sales.csv` — project dataset
- `docs/Discount_Sales_Project_Summary.docx` — project planning summary
- `install_packages.R` — installs required R packages
- `.gitignore` — keeps local RStudio files out of GitHub

## How to Open

1. Download and unzip the project folder.
2. Double-click `IBM-6540-Group-Project.Rproj`.
3. Open `Group1-Proposal-Presentation.qmd` in RStudio.

## How to Render

In the RStudio Console, run:

```r
quarto::quarto_render("Group1-Proposal-Presentation.qmd")
```

The QMD searches recursively for a CSV file with `retail` or `sales` in the file name, so it should automatically use `data/Retail_sales.csv`.

## GitHub Repo

Target repo:

```text
https://github.com/mjshawell/IBM-6540-Group-Project
```
