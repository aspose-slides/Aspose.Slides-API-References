---
title: ShapeElement
second_title: Aspose.Slides for Java API Reference
description: Represents a part of shape with same outline and fill properties.
type: docs
weight: 487
url: /java/com.aspose.slides/shapeelement/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IShapeElement](../../com.aspose.slides/ishapeelement)
```
public class ShapeElement implements IShapeElement
```

Represents a part of shape with same outline and fill properties.
## Methods

| Method | Description |
| --- | --- |
| [getParentShape()](#getParentShape--) | Returns a Shape\_PPT for which element was created. |
| [getGraphicsPath()](#getGraphicsPath--) | Returns an element's path. |
| [getFillSource()](#getFillSource--) | Returns information about how to fill an element. |
| [getStrokeSource()](#getStrokeSource--) | Returns information about how to stroke an element. |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```


Returns a Shape\_PPT for which element was created. Read-only [Shape](../../com.aspose.slides/shape).

**Returns:**
[Shape](../../com.aspose.slides/shape)
### getGraphicsPath() {#getGraphicsPath--}
```
public Shape getGraphicsPath()
```


Returns an element's path. Read-only java.awt.geom.GeneralPath.

**Returns:**
[Shape](../../java.awt/shape)
### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```


Returns information about how to fill an element. Read-only [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource).

**Returns:**
byte
### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```


Returns information about how to stroke an element. Read-only [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource).

**Returns:**
byte
