---
title: HtmlOptions
type: docs
weight: 0
url: /php-java/htmloptions/
---

# HtmlOptions class

 Represents a HTML exporting options.
 

## Constructors

| name | description |
| --- | --- |
| [HtmlOptions](/php-java/htmloptions/htmloptions/)(ILinkEmbedController) | Creates a new HtmlOptions object specifiing callback. |
| [HtmlOptions](/php-java/htmloptions/htmloptions/)() | Creates a new HtmlOptions object for saving into single HTML file. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getDeletePicturesCroppedAreas](/php-java/htmloptions/getdeletepicturescroppedareas/)() | boolean | A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped parts will removed, if false they will be serialized in the document (which can possible lead to a larger file) |
| [getHtmlFormatter](/php-java/htmloptions/gethtmlformatter/)() | IHtmlFormatter | Returns or sets HTML template. Read/write IHtmlFormatter. |
| [getJpegQuality](/php-java/htmloptions/getjpegquality/)() | byte | Returns or sets a value determining the quality of the JPEG images inside PDF document. Read/write byte. Has effect only when a document contains JPEG images. Use this property to get or set the quality of the images inside a document when saving in PDF format. The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression. The default value is 95. |
| [getNotesCommentsLayouting](/php-java/htmloptions/getnotescommentslayouting/)() | INotesCommentsLayoutingOptions | Provides options that control how notes and comments is placed in exported document. |
| [getPicturesCompression](/php-java/htmloptions/getpicturescompression/)() | int | Represents the pictures compression level |
| [getShowHiddenSlides](/php-java/htmloptions/getshowhiddenslides/)() | boolean | Specifies whether the generated document should include hidden slides or not. Default is false. |
| [getSlideImageFormat](/php-java/htmloptions/getslideimageformat/)() | ISlideImageFormat | Returns or sets slide image format options. Read/write ISlideImageFormat. |
| [getSvgResponsiveLayout](/php-java/htmloptions/getsvgresponsivelayout/)() | boolean | True to exclude width and height attributes from svg container - that will make layout responsive. False - otherwise. Read/write boolean. |
| [setDeletePicturesCroppedAreas](/php-java/htmloptions/setdeletepicturescroppedareas/)(boolean) | void | A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped parts will removed, if false they will be serialized in the document (which can possible lead to a larger file) |
| [setHtmlFormatter](/php-java/htmloptions/sethtmlformatter/)(IHtmlFormatter) | void | Returns or sets HTML template. Read/write IHtmlFormatter. |
| [setJpegQuality](/php-java/htmloptions/setjpegquality/)(byte) | void | Returns or sets a value determining the quality of the JPEG images inside PDF document. Read/write byte. Has effect only when a document contains JPEG images. Use this property to get or set the quality of the images inside a document when saving in PDF format. The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression. The default value is 95. |
| [setPicturesCompression](/php-java/htmloptions/setpicturescompression/)(int) | void | Represents the pictures compression level |
| [setShowHiddenSlides](/php-java/htmloptions/setshowhiddenslides/)(boolean) | void | Specifies whether the generated document should include hidden slides or not. Default is false. |
| [setSlideImageFormat](/php-java/htmloptions/setslideimageformat/)(ISlideImageFormat) | void | Returns or sets slide image format options. Read/write ISlideImageFormat. |
| [setSvgResponsiveLayout](/php-java/htmloptions/setsvgresponsivelayout/)(boolean) | void | True to exclude width and height attributes from svg container - that will make layout responsive. False - otherwise. Read/write boolean. |
