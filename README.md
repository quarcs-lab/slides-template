# Slides template


## How to create PDF slides

### Manually

Various approaches exist converting HTML slides to PDF. One way is to print the slides to PDF using your web browser (e.g. Ctrl + P or Command + P in Google Chrome). Firefox is not supported, Chrome should work best.

### With a package

```
library(webshot)
webshot::install_phantomjs(force = TRUE)
```
```
webshot("index.html", "index.pdf")
```
