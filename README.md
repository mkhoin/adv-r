# Advanced R 한국어 번역 프로젝트

[![Build Status](https://travis-ci.org/advrkr/adv-r.svg?branch=master)](https://travis-ci.org/advrkr/adv-r)
[![Netlify Status](https://api.netlify.com/api/v1/badges/5f44615c-61a2-4481-80ca-dcfa21e31f4b/deploy-status)](https://app.netlify.com/sites/advrkr/deploys)


This is code and text behind the [Advanced R](http://adv-r.hadley.nz)
book.  The site is built with [bookdown](https://bookdown.org/yihui/bookdown/).

## Diagrams

Omnigraffle:
  
* Make sure that 100% is "one postscript point": this ensures canvas
  size matches physical size. Export at 300 dpi scaled to 100%.

* Set grid to 1cm with 10 minor units. Ensure there is 2mm padding around
  all sides of each diagram.

* Conventions:
    * Text is set in inconsolata 10pt, with text padding set to 3. 
    * Emoji set in "Apple Color Emoji" 8pt.
    * Default scalar size is 6mm x 6mm.
    * Symbols have 4pt rounded corners and plum border.
    * Arrow heads should be set to 75%.
    * Names should be coloured in steel.

Book:

* Inconsolata scaled (by fontspec) to match main font is 9.42pt.

* Preview at 100% matches physical size of book. Maxiumum diagram width is 11cm.

RMarkdown

* Remove dpi specification from `include_graphics()`, instead relying
  on `common.R`. Chunk should have `output.width = NULL`.

* Beware caching: after changing the size of an image you may need to
  clear the cache before it is correctly updated.

## Code of conduct

Please note that Advanced R is released with a [Contributor Code of Conduct](CODE_OF_CONDUCT.md).
By contributing to this project, you agree to abide by its terms.
