---
title: ISvgShapeFormattingController
second_title: Aspose.Slides for Android via Java API Reference
description: Controls SVG shape generation.
type: docs
weight: 1056
url: /androidjava/com.aspose.slides/isvgshapeformattingcontroller/
---```
public interface ISvgShapeFormattingController
```

Controls SVG shape generation.
## Methods

| Method | Description |
| --- | --- |
| [formatShape(ISvgShape svgShape, IShape shape)](#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-) | This function is called before rendering of shape to SVG to allow user to control resulting SVG. |
### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public abstract void formatShape(ISvgShape svgShape, IShape shape)
```


This function is called before rendering of shape to SVG to allow user to control resulting SVG.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) | Object to control SVG shape generation. |
| shape | [IShape](../../com.aspose.slides/ishape) | Source shape. |

