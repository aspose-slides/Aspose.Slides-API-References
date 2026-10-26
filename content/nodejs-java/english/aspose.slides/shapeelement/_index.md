---
title: ShapeElement
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/shapeelement/
---

## ShapeElement class

 Represents a part of shape with same outline and fill properties.
 
### getFillSource {#getFillSource}

| Name | Description |
| --- | --- |
| getFillSource () | Returns information about how to fill an element. Read-only ShapeElementFillSource. |

 **Returns:**
byte


---


### getParentShape {#getParentShape}

| Name | Description |
| --- | --- |
| getParentShape () | Returns a Shape_PPT for which element was created. Read-only Shape. |

 **Returns:**
Shape


---


### getPathPoints {#getPathPoints}

| Name | Description |
| --- | --- |
| getPathPoints () | Gets an array of points that define the geometry of the element's path. |

 **Returns:**
Point2D.Float


---


### getPathTypes {#getPathTypes}

| Name | Description |
| --- | --- |
| getPathTypes () | Gets an array of byte values that specify the type of each point in the element's path. 0 Indicates that the point is the start of a figure. 1 Indicates that the point is one of the two endpoints of a line. 3 Indicates that the point is an endpoint or control point of a cubic Bezier spline. 7 Masks all bits except for the three low-order bits, which indicate the point type. 16 Specifies that the corresponding segment is dashed. 32 Specifies that the point is a marker. 128 Specifies that the point is the last point in a closed subpath (figure). 129 Indicates a data point that is both a line segment endpoint and the last point of a closed subpath. |

 **Returns:**
byte


---


### getStrokeSource {#getStrokeSource}

| Name | Description |
| --- | --- |
| getStrokeSource () | Returns information about how to stroke an element. Read-only ShapeElementStrokeSource. |

 **Returns:**
byte


---


