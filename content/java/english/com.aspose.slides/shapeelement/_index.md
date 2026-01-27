---
title: ShapeElement
second_title: Aspose.Slides for Java API Reference
description: Represents a part of shape with same outline and fill properties.
type: docs
url: /com.aspose.slides/shapeelement/
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
| [getPathPoints()](#getPathPoints--) | Gets an array of points that define the geometry of the element's path. |
| [getPathTypes()](#getPathTypes--) | Gets an array of byte values that specify the type of each point in the element's path. |
| [getFillSource()](#getFillSource--) | Returns information about how to fill an element. |
| [getStrokeSource()](#getStrokeSource--) | Returns information about how to stroke an element. |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```


Returns a Shape\_PPT for which element was created. Read-only [Shape](../../com.aspose.slides/shape).

**Returns:**
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final Point2D.Float[] getPathPoints()
```


Gets an array of points that define the geometry of the element's path.

**Returns:**
java.awt.geom.Point2D.Float[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```


Gets an array of byte values that specify the type of each point in the element's path.

 **0**  Indicates that the point is the start of a figure.

 **1**  Indicates that the point is one of the two endpoints of a line.

 **3**  Indicates that the point is an endpoint or control point of a cubic Bezier spline.

 **7**  Masks all bits except for the three low-order bits, which indicate the point type.

 **16**  Specifies that the corresponding segment is dashed.

 **32**  Specifies that the point is a marker.

 **128**  Specifies that the point is the last point in a closed subpath (figure).

 **129**  Indicates a data point that is both a line segment endpoint and the last point of a closed subpath.

**Returns:**
byte[]
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
