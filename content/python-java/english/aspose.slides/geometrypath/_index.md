---
title: GeometryPath
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/geometrypath/
---

## GeometryPath class

 Represents geometry path of GeometryShape
 
### GeometryPath {#GeometryPath}

| Name | Description |
| --- | --- |
| GeometryPath() | Creates instance of GeometryPath |

 **Returns:**
GeometryPath


---


### arcTo {#arcTo}

| Name | Description |
| --- | --- |
| arcTo(float, float, float, float) | Appends the specified arc to the path. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| width | float | Width of the rectangle |
| heigth | float | Height of the rectangle |
| startAngle | float | Start angle. |
| sweepAngle | float | Sweep angle/ |


---


### closeFigure {#closeFigure}

| Name | Description |
| --- | --- |
| closeFigure() | Closes the current figure of this path |


---


### cubicBezierTo {#cubicBezierTo}

| Name | Description |
| --- | --- |
| cubicBezierTo(Point2D.Float, Point2D.Float, Point2D.Float) | Adds cubic Bezier curve at the end the path |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| point1 | Point2D.Float | First direction point |
| point2 | Point2D.Float | Second direction point |
| point3 | Point2D.Float | End point |


---


### cubicBezierTo {#cubicBezierTo}

| Name | Description |
| --- | --- |
| cubicBezierTo(float, float, float, float, float, float) | Adds cubic Bezier curve at the end the path |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x1 | float | X coordinate of first direction point |
| y1 | float | Y coordinate of first direction point |
| x2 | float | X coordinate of second direction point |
| y2 | float | Y coordinate of second direction point |
| x3 | float | X coordinate of end point |
| y3 | float | Y coordinate of end point |


---


### cubicBezierTo {#cubicBezierTo}

| Name | Description |
| --- | --- |
| cubicBezierTo(Point2D.Float, Point2D.Float, Point2D.Float, long) | Adds cubic Bezier curve to the specified place of the path |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| point1 | Point2D.Float | First direction point |
| point2 | Point2D.Float | Second direction point |
| point3 | Point2D.Float | End point |
| index | long | Index of segment in PathData |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | Segment index is out of PathData range |


---


### cubicBezierTo {#cubicBezierTo}

| Name | Description |
| --- | --- |
| cubicBezierTo(float, float, float, float, float, float, long) | Adds cubic Bezier curve to the specified place of the path |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x1 | float | X coordinate of first direction point |
| y1 | float | Y coordinate of first direction point |
| x2 | float | X coordinate of second direction point |
| y2 | float | Y coordinate of second direction point |
| x3 | float | X coordinate of end point |
| y3 | float | Y coordinate of end point |
| index | long | Index of segment in PathData |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | Segment index is out of PathData range |


---


### getFillMode {#getFillMode}

| Name | Description |
| --- | --- |
| getFillMode() | Sets fill mode |

 **Returns:**
byte


---


### getPathData {#getPathData}

| Name | Description |
| --- | --- |
| getPathData() | Returns geometry path of GeometryShape as an array of path segments. |

 **Returns:**
[PathSegment](../pathsegment)


---


### getStroke {#getStroke}

| Name | Description |
| --- | --- |
| getStroke() | Sets stroke appearance |

 **Returns:**
boolean


---


### lineTo {#lineTo}

| Name | Description |
| --- | --- |
| lineTo(Point2D.Float) | Adds line to the end of the path |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| point | Point2D.Float | End point of the line |


---


### lineTo {#lineTo}

| Name | Description |
| --- | --- |
| lineTo(float, float) | Adds line to the end of the path |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of the end point of the line |
| y | float | Y coordinate of the end point of the line |


---


### lineTo {#lineTo}

| Name | Description |
| --- | --- |
| lineTo(Point2D.Float, long) | Adds line to the specified place of the path |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| point | Point2D.Float | End point |
| index | long | Index of segment in PathData |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | Segment index is out of PathData range |


---


### lineTo {#lineTo}

| Name | Description |
| --- | --- |
| lineTo(float, float, long) | Adds line to the specified place of the path |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of the point |
| y | float | Y coordinate of the point |
| index | long | Index of segment in PathData |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | Segment index is out of PathData range |


---


### moveTo {#moveTo}

| Name | Description |
| --- | --- |
| moveTo(Point2D.Float) | Sets next point position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| point | Point2D.Float | Point position |


---


### moveTo {#moveTo}

| Name | Description |
| --- | --- |
| moveTo(float, float) | Sets next point position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of the point |
| y | float | Y Coordinate of the point |


---


### quadraticBezierTo {#quadraticBezierTo}

| Name | Description |
| --- | --- |
| quadraticBezierTo(Point2D.Float, Point2D.Float) | Adds quadratic Bezier curve at the end the path |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| point1 | Point2D.Float | Direction point |
| point2 | Point2D.Float | End point |


---


### quadraticBezierTo {#quadraticBezierTo}

| Name | Description |
| --- | --- |
| quadraticBezierTo(float, float, float, float) | Adds quadratic Bezier curve at the end the path |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x1 | float | X coordinate of direction point |
| y1 | float | Y coordinate of direction point |
| x2 | float | X coordinate of end point |
| y2 | float | Y coordinate of end point |


---


### quadraticBezierTo {#quadraticBezierTo}

| Name | Description |
| --- | --- |
| quadraticBezierTo(Point2D.Float, Point2D.Float, long) | Adds quadratic Bezier curve to the specified place of the path |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| point1 | Point2D.Float | Direction point |
| point2 | Point2D.Float | End point |
| index | long | Index of segment in PathData |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | Segment index is out of PathData range |


---


### quadraticBezierTo {#quadraticBezierTo}

| Name | Description |
| --- | --- |
| quadraticBezierTo(float, float, float, float, long) | Adds quadratic Bezier curve to the specified place of the path |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| x1 | float | X coordinate of direction point |
| y1 | float | Y coordinate of direction point |
| x2 | float | X coordinate of end point |
| y2 | float | Y coordinate of end point |
| index | long | Index of segment in PathData |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | Segment index is out of PathData range |


---


### removeAt {#removeAt}

| Name | Description |
| --- | --- |
| removeAt(int) | Removes segment at the specified index of the geometry path. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of the geometry path that should be deleted. |


---


### setFillMode {#setFillMode}

| Name | Description |
| --- | --- |
| setFillMode(byte) | Sets fill mode |


---


### setStroke {#setStroke}

| Name | Description |
| --- | --- |
| setStroke(boolean) | Sets stroke appearance |


---


