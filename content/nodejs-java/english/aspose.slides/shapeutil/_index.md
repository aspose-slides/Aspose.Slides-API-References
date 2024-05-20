---
title: ShapeUtil
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/shapeutil/
---

## ShapeUtil class

 Offer methods which helps to process shapes objects.
 
### ShapeUtil {#ShapeUtil}

| Name | Description |
| --- | --- |
| ShapeUtil() |  |

 **Returns:**
ShapeUtil


---


### geometryPathToGraphicsPath {#geometryPathToGraphicsPath}

| Name | Description |
| --- | --- |
| geometryPathToGraphicsPath ([GeometryPath](../geometrypath)) | Converts IGeometryPath to java.awt.Shape. GraphicsPath can be transformed in a different ways using its convenient functions and then transformed back into the IGeometryPath to use in GeometryShape via #graphicsPathToGeometryPath(java.awt.Shape) function. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| geometryPath | [GeometryPath](../geometrypath) |  |

 **Returns:**
Shape


---


### graphicsPathToGeometryPath {#graphicsPathToGeometryPath}

| Name | Description |
| --- | --- |
| graphicsPathToGeometryPath ([Shape](../shape)) | Converts a java.awt.Shape to the IGeometryPath |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| graphicsPath | [Shape](../shape) | Graphics path Return value of the function call can be used to change the geometry of a IGeometryShape object with IGeometryShape.SetGeometryPaths function. |

 **Returns:**
[GeometryPath](../geometrypath)


---


