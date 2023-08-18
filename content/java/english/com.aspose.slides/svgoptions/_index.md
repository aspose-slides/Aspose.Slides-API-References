---
title: SVGOptions
second_title: Aspose.Slides for Java API Reference
description: Represents an SVG options.
type: docs
weight: 474
url: /com.aspose.slides/svgoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**
[com.aspose.slides.ISVGOptions](../../com.aspose.slides/isvgoptions), java.lang.Cloneable
```
public final class SVGOptions extends SaveOptions implements ISVGOptions, Cloneable
```

Represents an SVG options.
## Constructors

| Constructor | Description |
| --- | --- |
| [SVGOptions()](#SVGOptions--) | Initializes a new instance of the SVGOptions class. |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | Initializes a new instance of the SVGOptions class specifying the link embedding controller object. |
## Methods

| Method | Description |
| --- | --- |
| [getUseFrameSize()](#getUseFrameSize--) | Determines whether the text frame will be included in a rendering area or not. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Determines whether the text frame will be included in a rendering area or not. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Determines whether to perform the specified rotation of the shape when rendering or not. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Determines whether to perform the specified rotation of the shape when rendering or not. |
| [getVectorizeText()](#getVectorizeText--) | Determines whether the text on a slide will be saved as graphics. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Determines whether the text on a slide will be saved as graphics. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Returns or sets the lower resolution limit for metafile rasterization. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Returns or sets the lower resolution limit for metafile rasterization. |
| [getDisable3DText()](#getDisable3DText--) | Determines whether the 3D text is disabled in SVG. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Determines whether the 3D text is disabled in SVG. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Disables splitting FromCornerX and FromCenter gradients. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Disables splitting FromCornerX and FromCenter gradients. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 lacks ability to define insets for markers. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 lacks ability to define insets for markers. |
| [getDefault()](#getDefault--) | Returns default settings. |
| [getSimple()](#getSimple--) | Returns settings for simpliest and smallest SVG file generation. |
| [getWYSIWYG()](#getWYSIWYG--) | Returns settings for most accurate SVG file generation. |
| [getJpegQuality()](#getJpegQuality--) | Determines JPEG encoding quality. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Determines JPEG encoding quality. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Returns and sets a callback interface which allows user to control shape conversion. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Returns and sets a callback interface which allows user to control shape conversion. |
| [getPicturesCompression()](#getPicturesCompression--) | Represents the pictures compression level |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Represents the pictures compression level |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | A boolean flag indicates if the cropped parts remain as part of the document. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | A boolean flag indicates if the cropped parts remain as part of the document. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Determines a way of handling externally loaded fonts. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Determines a way of handling externally loaded fonts. |
### SVGOptions() {#SVGOptions--}
```
public SVGOptions()
```


Initializes a new instance of the SVGOptions class.

### SVGOptions(ILinkEmbedController linkEmbedController) {#SVGOptions-com.aspose.slides.ILinkEmbedController-}
```
public SVGOptions(ILinkEmbedController linkEmbedController)
```


Initializes a new instance of the SVGOptions class specifying the link embedding controller object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | The link embedding controller reference.

--------------------

Link embedding controller is a delegate object that is responsible for making decisions if resources (such as images) need to be embedded or referenced as external resources. |

### getUseFrameSize() {#getUseFrameSize--}
```
public final boolean getUseFrameSize()
```


Determines whether the text frame will be included in a rendering area or not. Read/write  boolean . Default value is false.

**Returns:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```


Determines whether the text frame will be included in a rendering area or not. Read/write  boolean . Default value is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```


Determines whether to perform the specified rotation of the shape when rendering or not. Read/write  boolean . Default value is true.

**Returns:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```


Determines whether to perform the specified rotation of the shape when rendering or not. Read/write  boolean . Default value is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getVectorizeText() {#getVectorizeText--}
```
public final boolean getVectorizeText()
```


Determines whether the text on a slide will be saved as graphics. Read/write boolean.

**Returns:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public final void setVectorizeText(boolean value)
```


Determines whether the text on a slide will be saved as graphics. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```


Returns or sets the lower resolution limit for metafile rasterization. Read/write int.

**Returns:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```


Returns or sets the lower resolution limit for metafile rasterization. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public final boolean getDisable3DText()
```


Determines whether the 3D text is disabled in SVG. Read/write boolean.

**Returns:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public final void setDisable3DText(boolean value)
```


Determines whether the 3D text is disabled in SVG. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public final boolean getDisableGradientSplit()
```


Disables splitting FromCornerX and FromCenter gradients. Read/write boolean.

**Returns:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public final void setDisableGradientSplit(boolean value)
```


Disables splitting FromCornerX and FromCenter gradients. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public final boolean getDisableLineEndCropping()
```


SVG 1.1 lacks ability to define insets for markers. Aspose.Slides SVG writing engine has workaround for that problem: it crops end of line with arrow, so, line doesn't overlap markers. This option switches off such behavior. Read/write boolean.

**Returns:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```


SVG 1.1 lacks ability to define insets for markers. Aspose.Slides SVG writing engine has workaround for that problem: it crops end of line with arrow, so, line doesn't overlap markers. This option switches off such behavior. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDefault() {#getDefault--}
```
public static SVGOptions getDefault()
```


Returns default settings. Read-only [SVGOptions](../../com.aspose.slides/svgoptions).

**Returns:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getSimple() {#getSimple--}
```
public static SVGOptions getSimple()
```


Returns settings for simpliest and smallest SVG file generation. Read-only [SVGOptions](../../com.aspose.slides/svgoptions).

**Returns:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```


Returns settings for most accurate SVG file generation. Read-only [SVGOptions](../../com.aspose.slides/svgoptions).

**Returns:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```


Determines JPEG encoding quality. Read/write int.

**Returns:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```


Determines JPEG encoding quality. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public final ISvgShapeFormattingController getShapeFormattingController()
```


Returns and sets a callback interface which allows user to control shape conversion. Read/write [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Returns:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```


Returns and sets a callback interface which allows user to control shape conversion. Read/write [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```


Represents the pictures compression level

**Returns:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```


Represents the pictures compression level

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```


A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped parts will removed, if false they will be serialized in the document (which can possible lead to a larger file)

**Returns:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```


A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped parts will removed, if false they will be serialized in the document (which can possible lead to a larger file)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public final int getExternalFontsHandling()
```


Determines a way of handling externally loaded fonts. Read/write [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Returns:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public final void setExternalFontsHandling(int value)
```


Determines a way of handling externally loaded fonts. Read/write [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

