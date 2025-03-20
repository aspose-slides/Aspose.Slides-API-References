---
title: SVGOptions
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/svgoptions/
---

## SVGOptions class

 Represents an SVG options.
 
### SVGOptions {#SVGOptions}

| Name | Description |
| --- | --- |
| SVGOptions() | Initializes a new instance of the SVGOptions class. |

 **Returns:**
SVGOptions


---


### SVGOptions {#SVGOptions}

| Name | Description |
| --- | --- |
| SVGOptions([VideoPlayerHtmlController](../videoplayerhtmlcontroller)) | Initializes a new instance of the SVGOptions class specifying the link embedding controller object. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| linkEmbedController | [VideoPlayerHtmlController](../videoplayerhtmlcontroller) | The link embedding controller reference. Link embedding controller is a delegate object that is responsible for making decisions if resources (such as images) need to be embedded or referenced as external resources. |

 **Returns:**
SVGOptions


---


### getDefault {#getDefault}

| Name | Description |
| --- | --- |
| getDefault () | Returns default settings. Read-only SVGOptions. |

 **Returns:**
SVGOptions


---


### getDeletePicturesCroppedAreas {#getDeletePicturesCroppedAreas}

| Name | Description |
| --- | --- |
| getDeletePicturesCroppedAreas () | A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped parts will removed, if false they will be serialized in the document (which can possible lead to a larger file) |

 **Returns:**
boolean


---


### getDisable3DText {#getDisable3DText}

| Name | Description |
| --- | --- |
| getDisable3DText () | Determines whether the 3D text is disabled in SVG. Read/write boolean. |

 **Returns:**
boolean


---


### getDisableFontLigatures {#getDisableFontLigatures}

| Name | Description |
| --- | --- |
| getDisableFontLigatures () | Gets or sets a value indicating whether text is rendered without using ligatures. When set to true, ligatures will be disabled in the rendered output. By default, this property is set to false. |

 **Returns:**
boolean


---


### getDisableGradientSplit {#getDisableGradientSplit}

| Name | Description |
| --- | --- |
| getDisableGradientSplit () | Disables splitting FromCornerX and FromCenter gradients. Read/write boolean. |

 **Returns:**
boolean


---


### getDisableLineEndCropping {#getDisableLineEndCropping}

| Name | Description |
| --- | --- |
| getDisableLineEndCropping () | SVG 1.1 lacks ability to define insets for markers. Aspose.Slides SVG writing engine has workaround for that problem: it crops end of line with arrow, so, line doesn't overlap markers. This option switches off such behavior. Read/write boolean. |

 **Returns:**
boolean


---


### getExternalFontsHandling {#getExternalFontsHandling}

| Name | Description |
| --- | --- |
| getExternalFontsHandling () | Determines a way of handling externally loaded fonts. Read/write SvgExternalFontsHandling. |

 **Returns:**
int


---


### getInkOptions {#getInkOptions}

| Name | Description |
| --- | --- |
| getInkOptions () | Provides options that control the look of Ink objects in exported document. Read-only IInkOptions |

 **Returns:**
[InkOptions](../inkoptions)


---


### getJpegQuality {#getJpegQuality}

| Name | Description |
| --- | --- |
| getJpegQuality () | Determines JPEG encoding quality. Read/write int. |

 **Returns:**
int


---


### getMetafileRasterizationDpi {#getMetafileRasterizationDpi}

| Name | Description |
| --- | --- |
| getMetafileRasterizationDpi () | Returns or sets the lower resolution limit for metafile rasterization. Read/write int. |

 **Returns:**
int


---


### getPicturesCompression {#getPicturesCompression}

| Name | Description |
| --- | --- |
| getPicturesCompression () | Represents the pictures compression level |

 **Returns:**
int


---


### getShapeFormattingController {#getShapeFormattingController}

| Name | Description |
| --- | --- |
| getShapeFormattingController () | Returns and sets a callback interface which allows user to control shape conversion. Read/write ISvgShapeFormattingController. |

 **Returns:**
[VideoPlayerHtmlController](../videoplayerhtmlcontroller)


---


### getSimple {#getSimple}

| Name | Description |
| --- | --- |
| getSimple () | Returns settings for simpliest and smallest SVG file generation. Read-only SVGOptions. |

 **Returns:**
SVGOptions


---


### getUseFrameRotation {#getUseFrameRotation}

| Name | Description |
| --- | --- |
| getUseFrameRotation () | Determines whether to perform the specified rotation of the shape when rendering or not. Read/write boolean. Default value is true. |

 **Returns:**
boolean


---


### getUseFrameSize {#getUseFrameSize}

| Name | Description |
| --- | --- |
| getUseFrameSize () | Determines whether the text frame will be included in a rendering area or not. Read/write boolean. Default value is false. |

 **Returns:**
boolean


---


### getVectorizeText {#getVectorizeText}

| Name | Description |
| --- | --- |
| getVectorizeText () | Determines whether the text on a slide will be saved as graphics. Read/write boolean. |

 **Returns:**
boolean


---


### getWYSIWYG {#getWYSIWYG}

| Name | Description |
| --- | --- |
| getWYSIWYG () | Returns settings for most accurate SVG file generation. Read-only SVGOptions. |

 **Returns:**
SVGOptions


---


### setDeletePicturesCroppedAreas {#setDeletePicturesCroppedAreas}

| Name | Description |
| --- | --- |
| setDeletePicturesCroppedAreas (boolean) | A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped parts will removed, if false they will be serialized in the document (which can possible lead to a larger file) |

 **Returns:**
void


---


### setDisable3DText {#setDisable3DText}

| Name | Description |
| --- | --- |
| setDisable3DText (boolean) | Determines whether the 3D text is disabled in SVG. Read/write boolean. |

 **Returns:**
void


---


### setDisableFontLigatures {#setDisableFontLigatures}

| Name | Description |
| --- | --- |
| setDisableFontLigatures (boolean) | Gets or sets a value indicating whether text is rendered without using ligatures. When set to true, ligatures will be disabled in the rendered output. By default, this property is set to false. |

 **Returns:**
void


---


### setDisableGradientSplit {#setDisableGradientSplit}

| Name | Description |
| --- | --- |
| setDisableGradientSplit (boolean) | Disables splitting FromCornerX and FromCenter gradients. Read/write boolean. |

 **Returns:**
void


---


### setDisableLineEndCropping {#setDisableLineEndCropping}

| Name | Description |
| --- | --- |
| setDisableLineEndCropping (boolean) | SVG 1.1 lacks ability to define insets for markers. Aspose.Slides SVG writing engine has workaround for that problem: it crops end of line with arrow, so, line doesn't overlap markers. This option switches off such behavior. Read/write boolean. |

 **Returns:**
void


---


### setExternalFontsHandling {#setExternalFontsHandling}

| Name | Description |
| --- | --- |
| setExternalFontsHandling (int) | Determines a way of handling externally loaded fonts. Read/write SvgExternalFontsHandling. |

 **Returns:**
void


---


### setJpegQuality {#setJpegQuality}

| Name | Description |
| --- | --- |
| setJpegQuality (int) | Determines JPEG encoding quality. Read/write int. |

 **Returns:**
void


---


### setMetafileRasterizationDpi {#setMetafileRasterizationDpi}

| Name | Description |
| --- | --- |
| setMetafileRasterizationDpi (int) | Returns or sets the lower resolution limit for metafile rasterization. Read/write int. |

 **Returns:**
void


---


### setPicturesCompression {#setPicturesCompression}

| Name | Description |
| --- | --- |
| setPicturesCompression (int) | Represents the pictures compression level |

 **Returns:**
void


---


### setShapeFormattingController {#setShapeFormattingController}

| Name | Description |
| --- | --- |
| setShapeFormattingController ([VideoPlayerHtmlController](../videoplayerhtmlcontroller)) | Returns and sets a callback interface which allows user to control shape conversion. Read/write ISvgShapeFormattingController. |

 **Returns:**
void


---


### setUseFrameRotation {#setUseFrameRotation}

| Name | Description |
| --- | --- |
| setUseFrameRotation (boolean) | Determines whether to perform the specified rotation of the shape when rendering or not. Read/write boolean. Default value is true. |

 **Returns:**
void


---


### setUseFrameSize {#setUseFrameSize}

| Name | Description |
| --- | --- |
| setUseFrameSize (boolean) | Determines whether the text frame will be included in a rendering area or not. Read/write boolean. Default value is false. |

 **Returns:**
void


---


### setVectorizeText {#setVectorizeText}

| Name | Description |
| --- | --- |
| setVectorizeText (boolean) | Determines whether the text on a slide will be saved as graphics. Read/write boolean. |

 **Returns:**
void


---


