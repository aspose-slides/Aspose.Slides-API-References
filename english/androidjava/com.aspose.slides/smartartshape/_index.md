---
title: SmartArtShape
second_title: Aspose.Slides for Android via Java API Reference
description:  Represents SmartArt shape
type: docs
weight: 519
url: /androidjava/com.aspose.slides/smartartshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**All Implemented Interfaces:**
[com.aspose.slides.ISmartArtShape](../../com.aspose.slides/ismartartshape)
```
public class SmartArtShape extends GeometryShape implements ISmartArtShape
```

Represents SmartArt shape
## Methods

| Method | Description |
| --- | --- |
| [getShapeType()](#getShapeType--) | Returns or sets the geometry preset type. |
| [setShapeType(int value)](#setShapeType-int-) | Returns or sets the geometry preset type. |
| [getTextFrame()](#getTextFrame--) | Returns text of the SmartArt shape. |
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


Returns or sets the geometry preset type. Note: on value changing all adjustment values will reset to their default values. Read/write [ShapeType](../../com.aspose.slides/shapetype).

**Returns:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


Returns or sets the geometry preset type. Note: on value changing all adjustment values will reset to their default values. Read/write [ShapeType](../../com.aspose.slides/shapetype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```


Returns text of the SmartArt shape. Read-only [ITextFrame](../../com.aspose.slides/itextframe).

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe)
