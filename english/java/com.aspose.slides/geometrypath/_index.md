---
title: GeometryPath
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents geometry path of GeometryShape
type: docs
weight: 217
url: /java/com.aspose.slides/geometrypath/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IGeometryPath](../../com.aspose.slides/igeometrypath)
```
public final class GeometryPath implements IGeometryPath
```

Represents geometry path of GeometryShape
## Constructors

| Constructor | Description |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | Creates instance of GeometryPath |
| [GeometryPath(byte fillMode, boolean stroke)](#GeometryPath-byte-boolean-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getPathData()](#getPathData--) | Returns geometry path of GeometryShape as an array of path segments. |
| [removeAt(int index)](#removeAt-int-) | Removes segment at the specified index of the geometry path. |
| [lineTo(Point2D.Float point)](#lineTo-java.awt.geom.Point2D.Float-) | Adds line to the end of the path |
| [lineTo(float x, float y)](#lineTo-float-float-) | Adds line to the end of the path |
| [lineTo(Point2D.Float point, long index)](#lineTo-java.awt.geom.Point2D.Float-long-) | Adds line to the specified place of the path |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Adds line to the specified place of the path |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Adds cubic Bezier curve at the end the path |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Adds cubic Bezier curve at the end the path |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Adds cubic Bezier curve to the specified place of the path |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Adds cubic Bezier curve to the specified place of the path |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Adds quadratic Bezier curve at the end the path |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Adds quadratic Bezier curve at the end the path |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Adds quadratic Bezier curve to the specified place of the path |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Adds quadratic Bezier curve to the specified place of the path |
| [closeFigure()](#closeFigure--) | Closes the current figure of this path |
| [moveTo(Point2D.Float point)](#moveTo-java.awt.geom.Point2D.Float-) | Sets next point position. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Sets next point position. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Appends the specified arc to the path. |
| [getFillMode()](#getFillMode--) | Sets fill mode |
| [setFillMode(byte value)](#setFillMode-byte-) | Sets fill mode |
| [getStroke()](#getStroke--) | Sets stroke appearance |
| [setStroke(boolean value)](#setStroke-boolean-) | Sets stroke appearance |
### GeometryPath() {#GeometryPath--}
```
public GeometryPath()
```


Creates instance of GeometryPath

### GeometryPath(byte fillMode, boolean stroke) {#GeometryPath-byte-boolean-}
```
 GeometryPath(byte fillMode, boolean stroke)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fillMode | byte |  |
| stroke | boolean |  |

### getPathData() {#getPathData--}
```
public final IPathSegment[] getPathData()
```


Returns geometry path of GeometryShape as an array of path segments.

**Returns:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Removes segment at the specified index of the geometry path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of the geometry path that should be deleted. |

### lineTo(Point2D.Float point) {#lineTo-java.awt.geom.Point2D.Float-}
```
public final void lineTo(Point2D.Float point)
```


Adds line to the end of the path

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | End point of the line |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public final void lineTo(float x, float y)
```


Adds line to the end of the path

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of the end point of the line |
| y | float | Y coordinate of the end point of the line |

### lineTo(Point2D.Float point, long index) {#lineTo-java.awt.geom.Point2D.Float-long-}
```
public final void lineTo(Point2D.Float point, long index)
```


Adds line to the specified place of the path

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | End point |
| index | long | Index of segment in PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```


Adds line to the specified place of the path

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of the point |
| y | float | Y coordinate of the point |
| index | long | Index of segment in PathData |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)
```


Adds cubic Bezier curve at the end the path

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | First direction point |
| point2 | java.awt.geom.Point2D.Float | Second direction point |
| point3 | java.awt.geom.Point2D.Float | End point |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```


Adds cubic Bezier curve at the end the path

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | X coordinate of first direction point |
| y1 | float | Y coordinate of first direction point |
| x2 | float | X coordinate of second direction point |
| y2 | float | Y coordinate of second direction point |
| x3 | float | X coordinate of end point |
| y3 | float | Y coordinate of end point |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)
```


Adds cubic Bezier curve to the specified place of the path

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | First direction point |
| point2 | java.awt.geom.Point2D.Float | Second direction point |
| point3 | java.awt.geom.Point2D.Float | End point |
| index | long | Index of segment in PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```


Adds cubic Bezier curve to the specified place of the path

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | X coordinate of first direction point |
| y1 | float | Y coordinate of first direction point |
| x2 | float | X coordinate of second direction point |
| y2 | float | Y coordinate of second direction point |
| x3 | float | X coordinate of end point |
| y3 | float | Y coordinate of end point |
| index | long | Index of segment in PathData |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)
```


Adds quadratic Bezier curve at the end the path

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Direction point |
| point2 | java.awt.geom.Point2D.Float | End point |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```


Adds quadratic Bezier curve at the end the path

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | X coordinate of direction point |
| y1 | float | Y coordinate of direction point |
| x2 | float | X coordinate of end point |
| y2 | float | Y coordinate of end point |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)
```


Adds quadratic Bezier curve to the specified place of the path

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Direction point |
| point2 | java.awt.geom.Point2D.Float | End point |
| index | long | Index of segment in PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```


Adds quadratic Bezier curve to the specified place of the path

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | X coordinate of direction point |
| y1 | float | Y coordinate of direction point |
| x2 | float | X coordinate of end point |
| y2 | float | Y coordinate of end point |
| index | long | Index of segment in PathData |

### closeFigure() {#closeFigure--}
```
public final void closeFigure()
```


Closes the current figure of this path

### moveTo(Point2D.Float point) {#moveTo-java.awt.geom.Point2D.Float-}
```
public final void moveTo(Point2D.Float point)
```


Sets next point position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Point position |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public final void moveTo(float x, float y)
```


Sets next point position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of the point |
| y | float | Y Coordinate of the point |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public final void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```


Appends the specified arc to the path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | float | Width of the rectangle |
| heigth | float | Height of the rectangle |
| startAngle | float | Start angle. |
| sweepAngle | float | Sweep angle/ |

### getFillMode() {#getFillMode--}
```
public final byte getFillMode()
```


Sets fill mode

**Returns:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public final void setFillMode(byte value)
```


Sets fill mode

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public final boolean getStroke()
```


Sets stroke appearance

**Returns:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public final void setStroke(boolean value)
```


Sets stroke appearance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

