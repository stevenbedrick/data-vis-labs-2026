[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

# data-vis-labs-2026

See my blogdown demo site here: 

-https://ada-lovelace.netlify.com/blog/


And the GitHub repository for it here: 

- https://github.com/apreshill/ada-blog


## Notes on building the site

- In RStudio, from the Console, run `rmarkdown::render_site()` with the project root as the working directory.
  - Or use the "Build Site" button on the "Build" tab in the upper right-hand corner of the RStudio window! 🤦
- This won't re-knit the lecture slides; you'll need to do those manually.
- Various libraries and packages will need to be installed, and some of them are from Github via devtools. As such, RStudio won't find them automatically- you'll need to iterate a bit.
  - you'll also need `pagedown` for the slides
- For lab 5, make sure to run `extrafont::font_import()` before trying to knit!