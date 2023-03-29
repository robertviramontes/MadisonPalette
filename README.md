# MadisonPalette
R palette for plotting compatible with UW Madison themed presentations.

Colors taken from theming in PowerPoint templates, available here: 
https://brand.wisc.edu/multimedia/powerpoint/

`madison_categorical` provides 12 distinct colors, primarily intended for categorical plots. 

# Example
```
library("ggpubr")
library("MadisonPalette")
ggscatter(iris, x="Sepal.Length", y="Sepal.Width", color="Species", palette=madison_categorical)
```
![Example of scatter plot using the palette.](man/img/ex1.png)

# Installation
Check out [this post](https://cran.r-project.org/web/packages/githubinstall/vignettes/githubinstall.html) for information on installing packages from GitHub.

```
library("devtools")
install_github("robertviramontes/MadisonPalette")
```

# Disclaimer
This is meant as a quick tool to help UW Madison affliates prepare plots that integrate nicely with PowerPoint templates. Provided as-is with no support.
