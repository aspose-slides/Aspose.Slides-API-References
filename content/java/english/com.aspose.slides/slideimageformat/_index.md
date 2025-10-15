---
title: SlideImageFormat
second_title: Aspose.Slides for Java API Reference
description: Determines format in which slide image will be saved for presentation to HTML export.
type: docs
url: /com.aspose.slides/slideimageformat/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISlideImageFormat](../../com.aspose.slides/islideimageformat)
```
public class SlideImageFormat implements ISlideImageFormat
```

Determines format in which slide image will be saved for presentation to HTML export.
## Constructors

| Constructor | Description |
| --- | --- |
| [SlideImageFormat()](#SlideImageFormat--) |  |
## Methods

| Method | Description |
| --- | --- |
| [svg(SVGOptions options)](#svg-com.aspose.slides.SVGOptions-) | Slides should converted to a SVG format. |
| [bitmap(float scale, String imgFormat)](#bitmap-float-java.lang.String-) | Slides should be converted to a raster image. |
| [bitmap(float scale, int imageFormat)](#bitmap-float-int-) | Slides should be converted to a raster image. |
### SlideImageFormat() {#SlideImageFormat--}
```
public SlideImageFormat()
```


### svg(SVGOptions options) {#svg-com.aspose.slides.SVGOptions-}
```
public static SlideImageFormat svg(SVGOptions options)
```


Slides should converted to a SVG format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [SVGOptions](../../com.aspose.slides/svgoptions) | Options for SVG export. |

**Returns:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) - The [SlideImageFormat](../../com.aspose.slides/slideimageformat) object.
### bitmap(float scale, String imgFormat) {#bitmap-float-java.lang.String-}
```
public static SlideImageFormat bitmap(float scale, String imgFormat)
```


Slides should be converted to a raster image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scale | float | Image scale factor. |
| imgFormat | java.lang.String | Image format. |

**Returns:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) - The [SlideImageFormat](../../com.aspose.slides/slideimageformat) object.
### bitmap(float scale, int imageFormat) {#bitmap-float-int-}
```
public static SlideImageFormat bitmap(float scale, int imageFormat)
```


Slides should be converted to a raster image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scale | float | The factor by which to scale the output image. |
| imageFormat | int | The [ImageFormat](../../com.aspose.slides/imageformat) of the resulting image (e.g., PNG, JPEG). |

**Returns:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) - 
