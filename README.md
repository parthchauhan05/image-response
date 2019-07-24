# Image Response

## Introduction
Responsive Images is more than just making image grow and shrink. It is using the right image for any situation.

## Object
For this lab, you will use responsive image techniques and the files provided, make the right image appear on the web page.

## Requirements 
Follow the requirement below to update the web page to incorporate the techniques of responsive images.

1. Download the [Image Response starter files](https://github.com/MTM6230/image-response/archive/master.zip), and make the necessary changes to the `index.html` page, **No changes will need to be made to the `style.css` or to the images.**
2. Using the `srcset` attribute and the provided images, update `header__image` tag to allow the browser to choose the best available image.
3. Using the `srcset` and `sizes` attributes and the provided images, update the `footer__image` tag to allow the browser to choose the best available image. *Note: the image is being displayed at 80% of the viewport width (80vw).*
4. Using the `srcset` attribute and the provided images, to update the `<img>` tag inside the `main__image` tag to allow the browser to choose the best available image.
5. Add `<source>` tags with `media`, `sizes`, and `srcset` attributes to the `main__image` tag to change the image when certain media conditions are met:
    1. For windows between 768px and 1027px, using the images provided, allow the browser to choose the best available version of the `main-image-portrait` image. *Note: this image will be displayed at 50% of the viewport width (50vw).*
    2. For windows 1028px or larger, using the images provided, allow the browser to choose the best available verion of the `main-image-square` image. *Note: this image will be displayed at 33% of the viewport width (33vw).*
6. Add `<source>` tags with `media`, `sizes`, and `srcset` attributes to the `main__image` tag to add the image when certain media conditions are met: 
    1. For windows between 768px and 1027px, using the images provided, allow the browser to choose the best available version of the `main-image-landscape` image. *Note: this image will be displayed at 50% of the viewport width (50vw).*
    2. For all other conditions, no image should be displayed.