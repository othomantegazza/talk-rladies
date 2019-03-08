---
title: "Communicate your Results Elegantly with Rmarkdown"
author: "Otho Mantegazza"
output:
  word_document:
    reference_docx: templates/kjhealy-ref-mod2.docx
---

# Abstract

In data science, we need to **communicate** our results and observations. We communicate our results to **our team**, to a **wider audience** or sometimes  just to **ourselves** (just to remember what were doing in six months time).

If you work in R, you can communicate your results easily, because R is very well integrated with **Markdown**. This simplified markup language is a universal source to **.docx, .epub, .pdf** and, especially, **.html** files. Two packages, **Rmarkdown** and **knitr**, litteraly knit together R code and markdown text.

These packages run your R code, style your text and show the results in a single output. In this way you can produce elegant and reproducible reports.

Since markdown is **native to HTML**, also its integration in R works best with html outputs (luckily today we communicate mostly online). R has a wide ecosystem of packages that you can use to integrate your data analysis into HTML products, such as slides, books or a blog.

This opens a realm of possibilities to present your data analysis with web native technologies, to show your code and feed your results directly to static plots, but also to interactive apps, for example with leaflet for maps or d3 for dataviz.

In this workshop I'll show of how you can use those tools and what you can achieve with them, with practical exercises and examples of how I have been using those tools in the field of biology and genomics.
