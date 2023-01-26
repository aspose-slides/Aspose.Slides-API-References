---
title: SVGOptions
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/aspose.slides/svgoptions/
---

## SVGOptions class

 Represents an SVG options.
 

## Constructors

| Name | Description |
| --- | --- |
| [SVGOptions](svgoptions)() | Initializes a new instance of the SVGOptions class. |
| [SVGOptions](svgoptions)([VideoPlayerHtmlController](../videoplayerhtmlcontroller)) | Initializes a new instance of the SVGOptions class specifying the link embedding controller object. |

## Methods

| Name | Description |
| --- | --- |
| [getDefault](getdefault)() | Returns default settings. Read-only SVGOptions. |
| [getDeletePicturesCroppedAreas](getdeletepicturescroppedareas)() | A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped parts will removed, if false they will be serialized in the document (which can possible lead to a larger file) |
| [getDisable3DText](getdisable3dtext)() | Determines whether the 3D text is disabled in SVG. Read/write boolean. |
| [getDisableGradientSplit](getdisablegradientsplit)() | Disables splitting FromCornerX and FromCenter gradients. Read/write boolean. |
| [getDisableLineEndCropping](getdisablelineendcropping)() | SVG 1.1 lacks ability to define insets for markers. Aspose.Slides SVG writing engine has workaround for that problem: it crops end of line with arrow, so, line doesn't overlap markers. This option switches off such behavior. Read/write boolean. |
| [getExternalFontsHandling](getexternalfontshandling)() | Determines a way of handling externally loaded fonts. Read/write SvgExternalFontsHandling. |
| [getJpegQuality](getjpegquality)() | Determines JPEG encoding quality. Read/write int. |
| [getMetafileRasterizationDpi](getmetafilerasterizationdpi)() | Returns or sets the lower resolution limit for metafile rasterization. Read/write int. |
| [getPicturesCompression](getpicturescompression)() | Represents the pictures compression level |
| [getShapeFormattingController](getshapeformattingcontroller)() | Returns and sets a callback interface which allows user to control shape conversion. Read/write ISvgShapeFormattingController. |
| [getSimple](getsimple)() | Returns settings for simpliest and smallest SVG file generation. Read-only SVGOptions. |
| [getUseFrameRotation](getuseframerotation)() | Determines whether to perform the specified rotation of the shape when rendering or not. Read/write boolean. Default value is true. |
| [getUseFrameSize](getuseframesize)() | Determines whether the text frame will be included in a rendering area or not. Read/write boolean. Default value is false. |
| [getVectorizeText](getvectorizetext)() | Determines whether the text on a slide will be saved as graphics. Read/write boolean. |
| [getWYSIWYG](getwysiwyg)() | Returns settings for most accurate SVG file generation. Read-only SVGOptions. |
| [setDeletePicturesCroppedAreas](setdeletepicturescroppedareas)(boolean) | A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped parts will removed, if false they will be serialized in the document (which can possible lead to a larger file) |
| [setDisable3DText](setdisable3dtext)(boolean) | Determines whether the 3D text is disabled in SVG. Read/write boolean. |
| [setDisableGradientSplit](setdisablegradientsplit)(boolean) | Disables splitting FromCornerX and FromCenter gradients. Read/write boolean. |
| [setDisableLineEndCropping](setdisablelineendcropping)(boolean) | SVG 1.1 lacks ability to define insets for markers. Aspose.Slides SVG writing engine has workaround for that problem: it crops end of line with arrow, so, line doesn't overlap markers. This option switches off such behavior. Read/write boolean. |
| [setExternalFontsHandling](setexternalfontshandling)(int) | Determines a way of handling externally loaded fonts. Read/write SvgExternalFontsHandling. |
| [setJpegQuality](setjpegquality)(int) | Determines JPEG encoding quality. Read/write int. |
| [setMetafileRasterizationDpi](setmetafilerasterizationdpi)(int) | Returns or sets the lower resolution limit for metafile rasterization. Read/write int. |
| [setPicturesCompression](setpicturescompression)(int) | Represents the pictures compression level |
| [setShapeFormattingController](setshapeformattingcontroller)([VideoPlayerHtmlController](../videoplayerhtmlcontroller)) | Returns and sets a callback interface which allows user to control shape conversion. Read/write ISvgShapeFormattingController. |
| [setUseFrameRotation](setuseframerotation)(boolean) | Determines whether to perform the specified rotation of the shape when rendering or not. Read/write boolean. Default value is true. |
| [setUseFrameSize](setuseframesize)(boolean) | Determines whether the text frame will be included in a rendering area or not. Read/write boolean. Default value is false. |
| [setVectorizeText](setvectorizetext)(boolean) | Determines whether the text on a slide will be saved as graphics. Read/write boolean. |
