---
title: SmartArtShape
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents SmartArt shape
type: docs
weight: 519
url: /java/com.aspose.slides/smartartshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**All Implemented Interfaces:**
[com.aspose.slides.ISmartArtShape](../../com.aspose.slides/ismartartshape)
```
public class SmartArtShape extends GeometryShape implements ISmartArtShape
```

Represents SmartArt shape
## Constructors

| Constructor | Description |
| --- | --- |
| [SmartArtShape(IDOMObject parentImmediate, SmartArtShapeContainer container)](#SmartArtShape-com.aspose.slides.IDOMObject-com.aspose.slides.SmartArtShapeContainer-) | Initializes new instance of class [SmartArtShape](../../com.aspose.slides/smartartshape) |
## Methods

| Method | Description |
| --- | --- |
| [getShapeType()](#getShapeType--) | Returns or sets the geometry preset type. |
| [setShapeType(int value)](#setShapeType-int-) | Returns or sets the geometry preset type. |
| [getTextFrame()](#getTextFrame--) | Returns text of the SmartArt shape. |
### SmartArtShape(IDOMObject parentImmediate, SmartArtShapeContainer container) {#SmartArtShape-com.aspose.slides.IDOMObject-com.aspose.slides.SmartArtShapeContainer-}
```
 SmartArtShape(IDOMObject parentImmediate, SmartArtShapeContainer container)
```


Initializes new instance of class [SmartArtShape](../../com.aspose.slides/smartartshape)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentImmediate | com.aspose.slides.IDOMObject |  |
| container | com.aspose.slides.SmartArtShapeContainer | The SmartArtShapeContainer |

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
