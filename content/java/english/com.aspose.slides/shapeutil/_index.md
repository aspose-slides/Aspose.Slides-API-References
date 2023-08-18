---
title: ShapeUtil
second_title: Aspose.Slides for Java API Reference
description: Offer methods which helps to process shapes objects.
type: docs
weight: 497
url: /com.aspose.slides/shapeutil/
---
**Inheritance:**
java.lang.Object
```
public class ShapeUtil
```

Offer methods which helps to process shapes objects.
## Constructors

| Constructor | Description |
| --- | --- |
| [ShapeUtil()](#ShapeUtil--) |  |
## Methods

| Method | Description |
| --- | --- |
| [graphicsPathToGeometryPath(Shape graphicsPath)](#graphicsPathToGeometryPath-java.awt.Shape-) | Converts a java.awt.Shape to the [IGeometryPath](../../com.aspose.slides/igeometrypath) |
| [geometryPathToGraphicsPath(IGeometryPath geometryPath)](#geometryPathToGraphicsPath-com.aspose.slides.IGeometryPath-) | Converts [IGeometryPath](../../com.aspose.slides/igeometrypath) to java.awt.Shape. |
### ShapeUtil() {#ShapeUtil--}
```
public ShapeUtil()
```


### graphicsPathToGeometryPath(Shape graphicsPath) {#graphicsPathToGeometryPath-java.awt.Shape-}
```
public static IGeometryPath graphicsPathToGeometryPath(Shape graphicsPath)
```


Converts a java.awt.Shape to the [IGeometryPath](../../com.aspose.slides/igeometrypath)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| graphicsPath | java.awt.Shape | java.awt.Shape element.

--------------------

Return value of the method call can be used to change the geometry of a IGeometryShape object with IGeometryShape.setGeometryPaths() method. |

**Returns:**
[IGeometryPath](../../com.aspose.slides/igeometrypath) - IGeometryPath element.
### geometryPathToGraphicsPath(IGeometryPath geometryPath) {#geometryPathToGraphicsPath-com.aspose.slides.IGeometryPath-}
```
public static Shape geometryPathToGraphicsPath(IGeometryPath geometryPath)
```


Converts [IGeometryPath](../../com.aspose.slides/igeometrypath) to java.awt.Shape. GraphicsPath can be transformed in a different ways using its convenient methods and then transformed back into the [IGeometryPath](../../com.aspose.slides/igeometrypath) to use in [GeometryShape](../../com.aspose.slides/geometryshape) via \#graphicsPathToGeometryPath(java.awt.Shape graphicsPath).graphicsPathToGeometryPath(java.awt.Shape graphicsPath) method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| geometryPath | [IGeometryPath](../../com.aspose.slides/igeometrypath) | IGeometryPath element. |

**Returns:**
[Shape](../../java.awt/shape) - java.awt.Shape element.
