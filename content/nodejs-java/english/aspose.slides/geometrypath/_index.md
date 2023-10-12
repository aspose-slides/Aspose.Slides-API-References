---
title: GeometryPath
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/geometrypath/
---

## GeometryPath class

 Represents geometry path of GeometryShape
 
| [GeometryPath]() | Creates instance of GeometryPath |

### Result
GeometryPath


---


| [arcTo] ([float], [float], [float], [float]) | Appends the specified arc to the path. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| width | [float] | Width of the rectangle |
| heigth | [float] | Height of the rectangle |
| startAngle | [float] | Start angle. |
| sweepAngle | [float] | Sweep angle/ |


---


| [closeFigure] () | Closes the current figure of this path |


---


| [cubicBezierTo] ([Point2D.Float], [Point2D.Float], [Point2D.Float]) | Adds cubic Bezier curve at the end the path |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| point1 | [Point2D.Float] | First direction point |
| point2 | [Point2D.Float] | Second direction point |
| point3 | [Point2D.Float] | End point |


---


| [cubicBezierTo] ([float], [float], [float], [float], [float], [float]) | Adds cubic Bezier curve at the end the path |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x1 | [float] | X coordinate of first direction point |
| y1 | [float] | Y coordinate of first direction point |
| x2 | [float] | X coordinate of second direction point |
| y2 | [float] | Y coordinate of second direction point |
| x3 | [float] | X coordinate of end point |
| y3 | [float] | Y coordinate of end point |


---


| [cubicBezierTo] ([Point2D.Float], [Point2D.Float], [Point2D.Float], [long]) | Adds cubic Bezier curve to the specified place of the path |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| point1 | [Point2D.Float] | First direction point |
| point2 | [Point2D.Float] | Second direction point |
| point3 | [Point2D.Float] | End point |
| index | [long] | Index of segment in PathData |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | Segment index is out of PathData range |


---


| [cubicBezierTo] ([float], [float], [float], [float], [float], [float], [long]) | Adds cubic Bezier curve to the specified place of the path |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x1 | [float] | X coordinate of first direction point |
| y1 | [float] | Y coordinate of first direction point |
| x2 | [float] | X coordinate of second direction point |
| y2 | [float] | Y coordinate of second direction point |
| x3 | [float] | X coordinate of end point |
| y3 | [float] | Y coordinate of end point |
| index | [long] | Index of segment in PathData |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | Segment index is out of PathData range |


---


| [getFillMode] () | Sets fill mode |

### Result
byte


---


| [getPathData] () | Returns geometry path of GeometryShape as an array of path segments. |

### Result
[PathSegment]


---


| [getStroke] () | Sets stroke appearance |

### Result
boolean


---


| [lineTo] ([Point2D.Float]) | Adds line to the end of the path |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| point | [Point2D.Float] | End point of the line |


---


| [lineTo] ([float], [float]) | Adds line to the end of the path |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x | [float] | X coordinate of the end point of the line |
| y | [float] | Y coordinate of the end point of the line |


---


| [lineTo] ([Point2D.Float], [long]) | Adds line to the specified place of the path |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| point | [Point2D.Float] | End point |
| index | [long] | Index of segment in PathData |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | Segment index is out of PathData range |


---


| [lineTo] ([float], [float], [long]) | Adds line to the specified place of the path |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x | [float] | X coordinate of the point |
| y | [float] | Y coordinate of the point |
| index | [long] | Index of segment in PathData |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | Segment index is out of PathData range |


---


| [moveTo] ([Point2D.Float]) | Sets next point position. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| point | [Point2D.Float] | Point position |


---


| [moveTo] ([float], [float]) | Sets next point position. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x | [float] | X coordinate of the point |
| y | [float] | Y Coordinate of the point |


---


| [quadraticBezierTo] ([Point2D.Float], [Point2D.Float]) | Adds quadratic Bezier curve at the end the path |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| point1 | [Point2D.Float] | Direction point |
| point2 | [Point2D.Float] | End point |


---


| [quadraticBezierTo] ([float], [float], [float], [float]) | Adds quadratic Bezier curve at the end the path |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x1 | [float] | X coordinate of direction point |
| y1 | [float] | Y coordinate of direction point |
| x2 | [float] | X coordinate of end point |
| y2 | [float] | Y coordinate of end point |


---


| [quadraticBezierTo] ([Point2D.Float], [Point2D.Float], [long]) | Adds quadratic Bezier curve to the specified place of the path |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| point1 | [Point2D.Float] | Direction point |
| point2 | [Point2D.Float] | End point |
| index | [long] | Index of segment in PathData |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | Segment index is out of PathData range |


---


| [quadraticBezierTo] ([float], [float], [float], [float], [long]) | Adds quadratic Bezier curve to the specified place of the path |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x1 | [float] | X coordinate of direction point |
| y1 | [float] | Y coordinate of direction point |
| x2 | [float] | X coordinate of end point |
| y2 | [float] | Y coordinate of end point |
| index | [long] | Index of segment in PathData |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | Segment index is out of PathData range |


---


| [removeAt] ([int]) | Removes segment at the specified index of the geometry path. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of the geometry path that should be deleted. |


---


| [setFillMode] ([byte]) | Sets fill mode |


---


| [setStroke] ([boolean]) | Sets stroke appearance |


---


