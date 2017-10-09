# 01 Image formats

## Check the images for the correct format

PNGs are not always the solution. Are the PNGs in the document all needed?

## Solution

You can find possible improvements in the following commits:

 - [change images from png to jpg](https://github.com/stefanjudis/webperf-101-workshop-final/commit/ccfbaf51fb437a767045bb1c03f6930f0d399e74)
   - the header image (`header-bg.png`) and contact image (`map-image.png`) can be served as JPG
 - [add build process for webp and load it conditionally for `header-bg.jpg` and `map-image.jpg`](https://github.com/stefanjudis/webperf-101-workshop-final/commit/c67337044f4840309bc1e5ea7600d13bad22a36f)
   - also add feature detection in the head because webp in CSS is tricky