---
title: SVGOptions
second_title: Aspose.Sildes for Python via Java API Reference
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

 **Result:**
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

 **Result:**
SVGOptions


---


### getDefault {#getDefault}

| Name | Description |
| --- | --- |
| getDefault () | Returns default settings. Read-only SVGOptions. |

 **Result:**
SVGOptions


---


### getDefaultRegularFont {#getDefaultRegularFont}

| Name | Description |
| --- | --- |
| getDefaultRegularFont () | Returns or sets font used in case source font is not found. Read-write String. |

 **Result:**
String


---


### getDeletePicturesCroppedAreas {#getDeletePicturesCroppedAreas}

| Name | Description |
| --- | --- |
| getDeletePicturesCroppedAreas () | A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped parts will removed, if false they will be serialized in the document (which can possible lead to a larger file) |

 **Result:**
boolean


---


### getDisable3DText {#getDisable3DText}

| Name | Description |
| --- | --- |
| getDisable3DText () | Determines whether the 3D text is disabled in SVG. Read/write boolean. |

 **Result:**
boolean


---


### getDisableGradientSplit {#getDisableGradientSplit}

| Name | Description |
| --- | --- |
| getDisableGradientSplit () | Disables splitting FromCornerX and FromCenter gradients. Read/write boolean. |

 **Result:**
boolean


---


### getDisableLineEndCropping {#getDisableLineEndCropping}

| Name | Description |
| --- | --- |
| getDisableLineEndCropping () | SVG 1.1 lacks ability to define insets for markers. Aspose.Slides SVG writing engine has workaround for that problem: it crops end of line with arrow, so, line doesn't overlap markers. This option switches off such behavior. Read/write boolean. |

 **Result:**
boolean


---


### getExternalFontsHandling {#getExternalFontsHandling}

| Name | Description |
| --- | --- |
| getExternalFontsHandling () | Determines a way of handling externally loaded fonts. Read/write SvgExternalFontsHandling. |

 **Result:**
int


---


### getJpegQuality {#getJpegQuality}

| Name | Description |
| --- | --- |
| getJpegQuality () | Determines JPEG encoding quality. Read/write int. |

 **Result:**
int


---


### getMetafileRasterizationDpi {#getMetafileRasterizationDpi}

| Name | Description |
| --- | --- |
| getMetafileRasterizationDpi () | Returns or sets the lower resolution limit for metafile rasterization. Read/write int. |

 **Result:**
int


---


### getPicturesCompression {#getPicturesCompression}

| Name | Description |
| --- | --- |
| getPicturesCompression () | Represents the pictures compression level |

 **Result:**
int


---


### getProgressCallback {#getProgressCallback}

| Name | Description |
| --- | --- |
| getProgressCallback () | Represents a callback object for saving progress updates in percentage. See IProgressCallback. |

 **Result:**
IProgressCallback


---


### getShapeFormattingController {#getShapeFormattingController}

| Name | Description |
| --- | --- |
| getShapeFormattingController () | Returns and sets a callback interface which allows user to control shape conversion. Read/write ISvgShapeFormattingController. |

 **Result:**
[VideoPlayerHtmlController](../videoplayerhtmlcontroller)


---


### getSimple {#getSimple}

| Name | Description |
| --- | --- |
| getSimple () | Returns settings for simpliest and smallest SVG file generation. Read-only SVGOptions. |

 **Result:**
SVGOptions


---


### getUseFrameRotation {#getUseFrameRotation}

| Name | Description |
| --- | --- |
| getUseFrameRotation () | Determines whether to perform the specified rotation of the shape when rendering or not. Read/write boolean. Default value is true. |

 **Result:**
boolean


---


### getUseFrameSize {#getUseFrameSize}

| Name | Description |
| --- | --- |
| getUseFrameSize () | Determines whether the text frame will be included in a rendering area or not. Read/write boolean. Default value is false. |

 **Result:**
boolean


---


### getVectorizeText {#getVectorizeText}

| Name | Description |
| --- | --- |
| getVectorizeText () | Determines whether the text on a slide will be saved as graphics. Read/write boolean. |

 **Result:**
boolean


---


### getWYSIWYG {#getWYSIWYG}

| Name | Description |
| --- | --- |
| getWYSIWYG () | Returns settings for most accurate SVG file generation. Read-only SVGOptions. |

 **Result:**
SVGOptions


---


### getWarningCallback {#getWarningCallback}

| Name | Description |
| --- | --- |
| getWarningCallback () | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted. Read/write IWarningCallback. |

 **Result:**
IWarningCallback


---


### setDefaultRegularFont {#setDefaultRegularFont}

| Name | Description |
| --- | --- |
| setDefaultRegularFont (String) | Returns or sets font used in case source font is not found. Read-write String. |


---


### setDeletePicturesCroppedAreas {#setDeletePicturesCroppedAreas}

| Name | Description |
| --- | --- |
| setDeletePicturesCroppedAreas (boolean) | A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped parts will removed, if false they will be serialized in the document (which can possible lead to a larger file) |


---


### setDisable3DText {#setDisable3DText}

| Name | Description |
| --- | --- |
| setDisable3DText (boolean) | Determines whether the 3D text is disabled in SVG. Read/write boolean. |


---


### setDisableGradientSplit {#setDisableGradientSplit}

| Name | Description |
| --- | --- |
| setDisableGradientSplit (boolean) | Disables splitting FromCornerX and FromCenter gradients. Read/write boolean. |


---


### setDisableLineEndCropping {#setDisableLineEndCropping}

| Name | Description |
| --- | --- |
| setDisableLineEndCropping (boolean) | SVG 1.1 lacks ability to define insets for markers. Aspose.Slides SVG writing engine has workaround for that problem: it crops end of line with arrow, so, line doesn't overlap markers. This option switches off such behavior. Read/write boolean. |


---


### setExternalFontsHandling {#setExternalFontsHandling}

| Name | Description |
| --- | --- |
| setExternalFontsHandling (int) | Determines a way of handling externally loaded fonts. Read/write SvgExternalFontsHandling. |


---


### setJpegQuality {#setJpegQuality}

| Name | Description |
| --- | --- |
| setJpegQuality (int) | Determines JPEG encoding quality. Read/write int. |


---


### setMetafileRasterizationDpi {#setMetafileRasterizationDpi}

| Name | Description |
| --- | --- |
| setMetafileRasterizationDpi (int) | Returns or sets the lower resolution limit for metafile rasterization. Read/write int. |


---


### setPicturesCompression {#setPicturesCompression}

| Name | Description |
| --- | --- |
| setPicturesCompression (int) | Represents the pictures compression level |


---


### setProgressCallback {#setProgressCallback}

| Name | Description |
| --- | --- |
| setProgressCallback ([IProgressCallback](../iprogresscallback)) | Represents a callback object for saving progress updates in percentage. See IProgressCallback. |


---


### setShapeFormattingController {#setShapeFormattingController}

| Name | Description |
| --- | --- |
| setShapeFormattingController ([VideoPlayerHtmlController](../videoplayerhtmlcontroller)) | Returns and sets a callback interface which allows user to control shape conversion. Read/write ISvgShapeFormattingController. |


---


### setUseFrameRotation {#setUseFrameRotation}

| Name | Description |
| --- | --- |
| setUseFrameRotation (boolean) | Determines whether to perform the specified rotation of the shape when rendering or not. Read/write boolean. Default value is true. |


---


### setUseFrameSize {#setUseFrameSize}

| Name | Description |
| --- | --- |
| setUseFrameSize (boolean) | Determines whether the text frame will be included in a rendering area or not. Read/write boolean. Default value is false. |


---


### setVectorizeText {#setVectorizeText}

| Name | Description |
| --- | --- |
| setVectorizeText (boolean) | Determines whether the text on a slide will be saved as graphics. Read/write boolean. |


---


### setWarningCallback {#setWarningCallback}

| Name | Description |
| --- | --- |
| setWarningCallback ([IWarningCallback](../iwarningcallback)) | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted. Read/write IWarningCallback. |


---


