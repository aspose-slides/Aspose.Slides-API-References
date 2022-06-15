---
title: SVGOptions
type: docs
weight: 0
url: /php-java/svgoptions/
---

# SVGOptions class

 Represents an SVG options.
 

## Constructors

| name | description |
| --- | --- |
| [SVGOptions](/slides/php-java/svgoptions/svgoptions/)() | Initializes a new instance of the SVGOptions class. |
| [SVGOptions](/slides/php-java/svgoptions/svgoptions/)(ILinkEmbedController) | Initializes a new instance of the SVGOptions class specifying the link embedding controller object. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getDefault](/slides/php-java/svgoptions/getdefault/)() | SVGOptions | Returns default settings. Read-only SVGOptions. |
| [getDeletePicturesCroppedAreas](/slides/php-java/svgoptions/getdeletepicturescroppedareas/)() | boolean | A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped parts will removed, if false they will be serialized in the document (which can possible lead to a larger file) |
| [getDisable3DText](/slides/php-java/svgoptions/getdisable3dtext/)() | boolean | Determines whether the 3D text is disabled in SVG. Read/write boolean. |
| [getDisableGradientSplit](/slides/php-java/svgoptions/getdisablegradientsplit/)() | boolean | Disables splitting FromCornerX and FromCenter gradients. Read/write boolean. |
| [getDisableLineEndCropping](/slides/php-java/svgoptions/getdisablelineendcropping/)() | boolean | SVG 1.1 lacks ability to define insets for markers. Aspose.Slides SVG writing engine has workaround for that problem: it crops end of line with arrow, so, line doesn't overlap markers. This option switches off such behavior. Read/write boolean. |
| [getExternalFontsHandling](/slides/php-java/svgoptions/getexternalfontshandling/)() | int | Determines a way of handling externally loaded fonts. Read/write SvgExternalFontsHandling. |
| [getJpegQuality](/slides/php-java/svgoptions/getjpegquality/)() | int | Determines JPEG encoding quality. Read/write int. |
| [getMetafileRasterizationDpi](/slides/php-java/svgoptions/getmetafilerasterizationdpi/)() | int | Returns or sets the lower resolution limit for metafile rasterization. Read/write int. |
| [getPicturesCompression](/slides/php-java/svgoptions/getpicturescompression/)() | int | Represents the pictures compression level |
| [getShapeFormattingController](/slides/php-java/svgoptions/getshapeformattingcontroller/)() | ISvgShapeFormattingController | Returns and sets a callback interface which allows user to control shape conversion. Read/write ISvgShapeFormattingController. |
| [getSimple](/slides/php-java/svgoptions/getsimple/)() | SVGOptions | Returns settings for simpliest and smallest SVG file generation. Read-only SVGOptions. |
| [getVectorizeText](/slides/php-java/svgoptions/getvectorizetext/)() | boolean | Determines whether the text on a slide will be saved as graphics. Read/write boolean. |
| [getWYSIWYG](/slides/php-java/svgoptions/getwysiwyg/)() | SVGOptions | Returns settings for most accurate SVG file generation. Read-only SVGOptions. |
| [setDeletePicturesCroppedAreas](/slides/php-java/svgoptions/setdeletepicturescroppedareas/)(boolean) | void | A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped parts will removed, if false they will be serialized in the document (which can possible lead to a larger file) |
| [setDisable3DText](/slides/php-java/svgoptions/setdisable3dtext/)(boolean) | void | Determines whether the 3D text is disabled in SVG. Read/write boolean. |
| [setDisableGradientSplit](/slides/php-java/svgoptions/setdisablegradientsplit/)(boolean) | void | Disables splitting FromCornerX and FromCenter gradients. Read/write boolean. |
| [setDisableLineEndCropping](/slides/php-java/svgoptions/setdisablelineendcropping/)(boolean) | void | SVG 1.1 lacks ability to define insets for markers. Aspose.Slides SVG writing engine has workaround for that problem: it crops end of line with arrow, so, line doesn't overlap markers. This option switches off such behavior. Read/write boolean. |
| [setExternalFontsHandling](/slides/php-java/svgoptions/setexternalfontshandling/)(int) | void | Determines a way of handling externally loaded fonts. Read/write SvgExternalFontsHandling. |
| [setJpegQuality](/slides/php-java/svgoptions/setjpegquality/)(int) | void | Determines JPEG encoding quality. Read/write int. |
| [setMetafileRasterizationDpi](/slides/php-java/svgoptions/setmetafilerasterizationdpi/)(int) | void | Returns or sets the lower resolution limit for metafile rasterization. Read/write int. |
| [setPicturesCompression](/slides/php-java/svgoptions/setpicturescompression/)(int) | void | Represents the pictures compression level |
| [setShapeFormattingController](/slides/php-java/svgoptions/setshapeformattingcontroller/)(ISvgShapeFormattingController) | void | Returns and sets a callback interface which allows user to control shape conversion. Read/write ISvgShapeFormattingController. |
| [setVectorizeText](/slides/php-java/svgoptions/setvectorizetext/)(boolean) | void | Determines whether the text on a slide will be saved as graphics. Read/write boolean. |
