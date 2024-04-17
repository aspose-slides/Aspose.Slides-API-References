---
title: ShapeUtil
second_title: Aspose.Sildes for Python via Java API Reference
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
| geometryPathToGraphicsPath([GeometryPath](../geometrypath)) | Converts IGeometryPath to java.awt.Shape. GraphicsPath can be transformed in a different ways using its convenient methods and then transformed back into the IGeometryPath to use in GeometryShape via #graphicsPathToGeometryPath(java.awt.Shape graphicsPath) method. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| geometryPath | [GeometryPath](../geometrypath) | IGeometryPath element. |

 **Returns:**
Shape


---


### graphicsPathToGeometryPath {#graphicsPathToGeometryPath}

| Name | Description |
| --- | --- |
| graphicsPathToGeometryPath([Shape](../shape)) | Converts a java.awt.Shape graphicsPath to the IGeometryPath |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| graphicsPath | [Shape](../shape) | java.awt.Shape element. Return value of the method call can be used to change the geometry of a IGeometryShape object with IGeometryShape.setGeometryPaths() method. |

 **Returns:**
[GeometryPath](../geometrypath)


---


