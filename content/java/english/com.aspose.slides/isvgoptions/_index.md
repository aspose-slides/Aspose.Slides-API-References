---
title: ISVGOptions
second_title: Aspose.Slides for Java API Reference
description: Represents an SVG options.
type: docs
url: /com.aspose.slides/isvgoptions/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISVGOptions extends ISaveOptions
```

Represents an SVG options.
## Methods

| Method | Description |
| --- | --- |
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
| [getJpegQuality()](#getJpegQuality--) | Determines JPEG encoding quality. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Determines JPEG encoding quality. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Returns and sets a callback interface which allows user to control shape conversion. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Returns and sets a callback interface which allows user to control shape conversion. |
| [getPicturesCompression()](#getPicturesCompression--) | Represents the pictures compression level Read/write [.getPicturesCompression](../../null/\#getPicturesCompression)/[.setPicturesCompression(int)](../../null/\#setPicturesCompression-int-). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Represents the pictures compression level Read/write [.getPicturesCompression](../../null/\#getPicturesCompression)/[.setPicturesCompression(int)](../../null/\#setPicturesCompression-int-). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | A boolean flag indicates if the cropped parts remain as part of the document. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | A boolean flag indicates if the cropped parts remain as part of the document. |
| [getUseFrameSize()](#getUseFrameSize--) | Determines whether the text frame will be included in a rendering area or not. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Determines whether the text frame will be included in a rendering area or not. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Determines whether to perform the specified rotation of the shape when rendering or not. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Determines whether to perform the specified rotation of the shape when rendering or not. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Determines a way of handling externally loaded fonts. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Determines a way of handling externally loaded fonts. |
| [getInkOptions()](#getInkOptions--) | Provides options that control the look of Ink objects in exported document. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Gets or sets a value indicating whether text is rendered without using ligatures. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Gets or sets a value indicating whether text is rendered without using ligatures. |
### getVectorizeText() {#getVectorizeText--}
```
public abstract boolean getVectorizeText()
```


Determines whether the text on a slide will be saved as graphics. Read/write boolean.

**Returns:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public abstract void setVectorizeText(boolean value)
```


Determines whether the text on a slide will be saved as graphics. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public abstract int getMetafileRasterizationDpi()
```


Returns or sets the lower resolution limit for metafile rasterization. Read/write int.

**Returns:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public abstract void setMetafileRasterizationDpi(int value)
```


Returns or sets the lower resolution limit for metafile rasterization. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public abstract boolean getDisable3DText()
```


Determines whether the 3D text is disabled in SVG. Read/write boolean.

**Returns:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public abstract void setDisable3DText(boolean value)
```


Determines whether the 3D text is disabled in SVG. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public abstract boolean getDisableGradientSplit()
```


Disables splitting FromCornerX and FromCenter gradients. Read/write boolean.

**Returns:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public abstract void setDisableGradientSplit(boolean value)
```


Disables splitting FromCornerX and FromCenter gradients. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public abstract boolean getDisableLineEndCropping()
```


SVG 1.1 lacks ability to define insets for markers. Aspose.Slides SVG writing engine has workaround for that problem: it crops end of line with arrow, so, line doesn't overlap markers. This option switches off such behavior. Read/write boolean.

**Returns:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public abstract void setDisableLineEndCropping(boolean value)
```


SVG 1.1 lacks ability to define insets for markers. Aspose.Slides SVG writing engine has workaround for that problem: it crops end of line with arrow, so, line doesn't overlap markers. This option switches off such behavior. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```


Determines JPEG encoding quality. Read/write int.

**Returns:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```


Determines JPEG encoding quality. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public abstract ISvgShapeFormattingController getShapeFormattingController()
```


Returns and sets a callback interface which allows user to control shape conversion. Read/write [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Returns:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public abstract void setShapeFormattingController(ISvgShapeFormattingController value)
```


Returns and sets a callback interface which allows user to control shape conversion. Read/write [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```


Represents the pictures compression level Read/write [.getPicturesCompression](../../null/\#getPicturesCompression)/[.setPicturesCompression(int)](../../null/\#setPicturesCompression-int-).

**Returns:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```


Represents the pictures compression level Read/write [.getPicturesCompression](../../null/\#getPicturesCompression)/[.setPicturesCompression(int)](../../null/\#setPicturesCompression-int-).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```


A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped parts will removed, if false they will be serialized in the document (which can possible lead to a larger file) Read/write boolean.

**Returns:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```


A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped parts will removed, if false they will be serialized in the document (which can possible lead to a larger file) Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameSize() {#getUseFrameSize--}
```
public abstract boolean getUseFrameSize()
```


Determines whether the text frame will be included in a rendering area or not. Read/write  boolean . Default value is false.

**Returns:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public abstract void setUseFrameSize(boolean value)
```


Determines whether the text frame will be included in a rendering area or not. Read/write  boolean . Default value is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public abstract boolean getUseFrameRotation()
```


Determines whether to perform the specified rotation of the shape when rendering or not. Read/write  boolean . Default value is true.

**Returns:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public abstract void setUseFrameRotation(boolean value)
```


Determines whether to perform the specified rotation of the shape when rendering or not. Read/write  boolean . Default value is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public abstract int getExternalFontsHandling()
```


Determines a way of handling externally loaded fonts. Read/write [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Returns:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public abstract void setExternalFontsHandling(int value)
```


Determines a way of handling externally loaded fonts. Read/write [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```


Provides options that control the look of Ink objects in exported document. Read-only [IInkOptions](../../com.aspose.slides/iinkoptions)

**Returns:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```


Gets or sets a value indicating whether text is rendered without using ligatures. When set to true, ligatures will be disabled in the rendered output. By default, this property is set to false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```


Gets or sets a value indicating whether text is rendered without using ligatures. When set to true, ligatures will be disabled in the rendered output. By default, this property is set to false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

