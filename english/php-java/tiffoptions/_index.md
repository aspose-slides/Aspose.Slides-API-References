---
title: TiffOptions
type: docs
weight: 0
url: /php-java/tiffoptions/
---

# TiffOptions class

 Provides options that control how a presentation is saved in TIFF format.
 

## Constructors

| name | description |
| --- | --- |
| [TiffOptions](/php-java/tiffoptions/tiffoptions/)() | Default constructor. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getCompressionType](/php-java/tiffoptions/getcompressiontype/)() | int | Specifies the compression type. Read/write TiffCompressionTypes. |
| [getDpiX](/php-java/tiffoptions/getdpix/)() | long | Specifies the horizontal resolution in dots per inch. Read/write long. |
| [getDpiY](/php-java/tiffoptions/getdpiy/)() | long | Specifies the vertical resolution in dots per inch. Read/write long. |
| [getImageSize](/php-java/tiffoptions/getimagesize/)() | Dimension | Specifies size of a generated TIFF image. Default value is 0x0, what means that generated image sizes will be calculated based on presentation slide size value. Read/write java.awt.Dimension. |
| [getNotesCommentsLayouting](/php-java/tiffoptions/getnotescommentslayouting/)() | INotesCommentsLayoutingOptions | Provides options that control how notes and comments is placed in exported document. |
| [getPixelFormat](/php-java/tiffoptions/getpixelformat/)() | int | Specifies the pixel format for the generated images. Read/write ImagePixelFormat. |
| [getShowHiddenSlides](/php-java/tiffoptions/getshowhiddenslides/)() | boolean | Specifies whether the generated document should include hidden slides or not. Default is false. |
| [setCompressionType](/php-java/tiffoptions/setcompressiontype/)(int) | void | Specifies the compression type. Read/write TiffCompressionTypes. |
| [setDpiX](/php-java/tiffoptions/setdpix/)(long) | void | Specifies the horizontal resolution in dots per inch. Read/write long. |
| [setDpiY](/php-java/tiffoptions/setdpiy/)(long) | void | Specifies the vertical resolution in dots per inch. Read/write long. |
| [setImageSize](/php-java/tiffoptions/setimagesize/)(Dimension) | void | Specifies size of a generated TIFF image. Default value is 0x0, what means that generated image sizes will be calculated based on presentation slide size value. Read/write java.awt.Dimension. |
| [setPixelFormat](/php-java/tiffoptions/setpixelformat/)(int) | void | Specifies the pixel format for the generated images. Read/write ImagePixelFormat. |
| [setShowHiddenSlides](/php-java/tiffoptions/setshowhiddenslides/)(boolean) | void | Specifies whether the generated document should include hidden slides or not. Default is false. |
