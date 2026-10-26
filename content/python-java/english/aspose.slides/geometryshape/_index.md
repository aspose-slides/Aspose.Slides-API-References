---
title: GeometryShape
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/geometryshape/
---

## GeometryShape class

 Represents the parent class for all geometric shapes.
 
### createShapeElements {#createShapeElements}

| Name | Description |
| --- | --- |
| createShapeElements() | Creates and returns array of shape's elements. |

 **Returns:**
[ShapeElement](../shapeelement)


---


### getAdjustments {#getAdjustments}

| Name | Description |
| --- | --- |
| getAdjustments() | Returns a collection of shape's adjustment values. Read-only IAdjustValueCollection. |

 **Returns:**
[AdjustValueCollection](../adjustvaluecollection)


---


### getGeometryPaths {#getGeometryPaths}

| Name | Description |
| --- | --- |
| getGeometryPaths() | Returns the copy of path of the geometry shape. Coordinates are relative to the left top corner of the shape. |

 **Returns:**
[GeometryPath](../geometrypath)


---


### getShapeStyle {#getShapeStyle}

| Name | Description |
| --- | --- |
| getShapeStyle() | Returns shape's style object. Read-only IShapeStyle. |

 **Returns:**
[ShapeStyle](../shapestyle)


---


### getShapeType {#getShapeType}

| Name | Description |
| --- | --- |
| getShapeType() | Returns or sets the geometry preset type. Note: on value changing all adjustment values will reset to their default values. Read/write ShapeType. |

 **Returns:**
int


---


### setGeometryPath {#setGeometryPath}

| Name | Description |
| --- | --- |
| setGeometryPath([GeometryPath](../geometrypath)) | Updates shape geometry from IGeometryPath object. Coordinates must be relative to the left top corner of the shape. Changes the type of the shape (ShapeType( #getShapeType/ #setShapeType(int))) to ShapeType#Custom. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| geometryPath | [GeometryPath](../geometrypath) | Geometry path |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Empty path found |


---


### setGeometryPaths {#setGeometryPaths}

| Name | Description |
| --- | --- |
| setGeometryPaths(com.aspose.slides.IGeometryPath[]) | Updates shape geometry from array of IGeometryPath. Coordinates must be relative to the left top corner of the shape. Changes the type of the shape (ShapeType( #getShapeType/ #setShapeType(int))) to ShapeType#Custom. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| geometryPaths | com.aspose.slides.IGeometryPath[] | Array geometry paths |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Empty path |


---


### setShapeType {#setShapeType}

| Name | Description |
| --- | --- |
| setShapeType(int) | Returns or sets the geometry preset type. Note: on value changing all adjustment values will reset to their default values. Read/write ShapeType. |


---


