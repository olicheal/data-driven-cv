# cv

This repo contains the source-code of my CV built with RMarkdown, the [`pagedown`](https://github.com/rstudio/pagedown) package and the [`datadrivencv`](http://nickstrayer.me/datadrivencv/) framework - to which I have added a few tweaks of my own. It converts a Google Sheet of CV entries into a beautiful pdf or html doc.

## Contents:

- `cv.Rmd`: Source template for the CV, contains a YAML variable `pdf_mode` in the header that changes styles for pdf vs html
- `render_cv.R`: R script for rendering both pdf and html version of CV at the same time
- `dd_cv.css`: A custom set of CSS styles that build on the default Pagedown “resume” template
- `cv_printing_functions.R`: A series of functions that turn spreadsheet data into markdown/html and make that output work for PDF printing

*My CV data are not currenly public.*
