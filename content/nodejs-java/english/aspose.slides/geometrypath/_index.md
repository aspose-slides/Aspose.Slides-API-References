---
title: GeometryPath
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/geometrypath/
---

## GeometryPath class

 Represents geometry path of GeometryShape
 
| Name | Description |
| --- | --- |
| GeometryPath() | Creates instance of GeometryPath |

### Result
GeometryPath


---


| Name | Description |
| --- | --- |
| arcTo (float, float, float, float) | Appends the specified arc to the path. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| width | float | Width of the rectangle |
| heigth | float | Height of the rectangle |
| startAngle | float | Start angle. |
| sweepAngle | float | Sweep angle/ |


---


| Name | Description |
| --- | --- |
| closeFigure () | Closes the current figure of this path |


---


| Name | Description |
| --- | --- |
| cubicBezierTo (Point2D.Float, Point2D.Float, Point2D.Float) | Adds cubic Bezier curve at the end the path |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| point1 | Point2D.Float | First direction point |
| point2 | Point2D.Float | Second direction point |
| point3 | Point2D.Float | End point |


---


| Name | Description |
| --- | --- |
| cubicBezierTo (float, float, float, float, float, float) | Adds cubic Bezier curve at the end the path |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x1 | float | X coordinate of first direction point |
| y1 | float | Y coordinate of first direction point |
| x2 | float | X coordinate of second direction point |
| y2 | float | Y coordinate of second direction point |
| x3 | float | X coordinate of end point |
| y3 | float | Y coordinate of end point |


---


| Name | Description |
| --- | --- |
| cubicBezierTo (Point2D.Float, Point2D.Float, Point2D.Float, long) | Adds cubic Bezier curve to the specified place of the path |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| point1 | Point2D.Float | First direction point |
| point2 | Point2D.Float | Second direction point |
| point3 | Point2D.Float | End point |
| index | long | Index of segment in PathData |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | Segment index is out of PathData range |


---


| Name | Description |
| --- | --- |
| cubicBezierTo (float, float, float, float, float, float, long) | Adds cubic Bezier curve to the specified place of the path |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x1 | float | X coordinate of first direction point |
| y1 | float | Y coordinate of first direction point |
| x2 | float | X coordinate of second direction point |
| y2 | float | Y coordinate of second direction point |
| x3 | float | X coordinate of end point |
| y3 | float | Y coordinate of end point |
| index | long | Index of segment in PathData |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | Segment index is out of PathData range |


---


| Name | Description |
| --- | --- |
| getFillMode () | Sets fill mode |

### Result
byte


---


| Name | Description |
| --- | --- |
| getPathData () | Returns geometry path of GeometryShape as an array of path segments. |

### Result
PathSegment(../../pathsegment)


---


| Name | Description |
| --- | --- |
| getStroke () | Sets stroke appearance |

### Result
boolean


---


| Name | Description |
| --- | --- |
| lineTo (Point2D.Float) | Adds line to the end of the path |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| point | Point2D.Float | End point of the line |


---


| Name | Description |
| --- | --- |
| lineTo (float, float) | Adds line to the end of the path |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of the end point of the line |
| y | float | Y coordinate of the end point of the line |


---


| Name | Description |
| --- | --- |
| lineTo (Point2D.Float, long) | Adds line to the specified place of the path |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| point | Point2D.Float | End point |
| index | long | Index of segment in PathData |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | Segment index is out of PathData range |


---


| Name | Description |
| --- | --- |
| lineTo (float, float, long) | Adds line to the specified place of the path |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of the point |
| y | float | Y coordinate of the point |
| index | long | Index of segment in PathData |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | Segment index is out of PathData range |


---


| Name | Description |
| --- | --- |
| moveTo (Point2D.Float) | Sets next point position. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| point | Point2D.Float | Point position |


---


| Name | Description |
| --- | --- |
| moveTo (float, float) | Sets next point position. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of the point |
| y | float | Y Coordinate of the point |


---


| Name | Description |
| --- | --- |
| quadraticBezierTo (Point2D.Float, Point2D.Float) | Adds quadratic Bezier curve at the end the path |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| point1 | Point2D.Float | Direction point |
| point2 | Point2D.Float | End point |


---


| Name | Description |
| --- | --- |
| quadraticBezierTo (float, float, float, float) | Adds quadratic Bezier curve at the end the path |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x1 | float | X coordinate of direction point |
| y1 | float | Y coordinate of direction point |
| x2 | float | X coordinate of end point |
| y2 | float | Y coordinate of end point |


---


| Name | Description |
| --- | --- |
| quadraticBezierTo (Point2D.Float, Point2D.Float, long) | Adds quadratic Bezier curve to the specified place of the path |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| point1 | Point2D.Float | Direction point |
| point2 | Point2D.Float | End point |
| index | long | Index of segment in PathData |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | Segment index is out of PathData range |


---


| Name | Description |
| --- | --- |
| quadraticBezierTo (float, float, float, float, long) | Adds quadratic Bezier curve to the specified place of the path |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x1 | float | X coordinate of direction point |
| y1 | float | Y coordinate of direction point |
| x2 | float | X coordinate of end point |
| y2 | float | Y coordinate of end point |
| index | long | Index of segment in PathData |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | Segment index is out of PathData range |


---


| Name | Description |
| --- | --- |
| removeAt (int) | Removes segment at the specified index of the geometry path. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of the geometry path that should be deleted. |


---


| Name | Description |
| --- | --- |
| setFillMode (byte) | Sets fill mode |


---


| Name | Description |
| --- | --- |
| setStroke (boolean) | Sets stroke appearance |


---


