---
title: ShapeUtil
second_title: Aspose.Slides for Android via Java API Reference
description: Offer methods which helps to process shapes objects.
type: docs
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
| [graphicsPathToGeometryPath(Path graphicsPath)](#graphicsPathToGeometryPath-android.graphics.Path-) | Converts a android.graphics.Path to the [IGeometryPath](../../com.aspose.slides/igeometrypath) |
| [geometryPathToGraphicsPath(IGeometryPath geometryPath)](#geometryPathToGraphicsPath-com.aspose.slides.IGeometryPath-) | Converts [IGeometryPath](../../com.aspose.slides/igeometrypath) to android.graphics.Path. |
### ShapeUtil() {#ShapeUtil--}
```
public ShapeUtil()
```


### graphicsPathToGeometryPath(Path graphicsPath) {#graphicsPathToGeometryPath-android.graphics.Path-}
```
public static IGeometryPath graphicsPathToGeometryPath(Path graphicsPath)
```


Converts a android.graphics.Path to the [IGeometryPath](../../com.aspose.slides/igeometrypath)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| graphicsPath | android.graphics.Path | Graphics path

--------------------

Return value of the method call can be used to change the geometry of a IGeometryShape object with IGeometryShape.SetGeometryPaths method. |

**Returns:**
[IGeometryPath](../../com.aspose.slides/igeometrypath) - Geometry path
### geometryPathToGraphicsPath(IGeometryPath geometryPath) {#geometryPathToGraphicsPath-com.aspose.slides.IGeometryPath-}
```
public static Path geometryPathToGraphicsPath(IGeometryPath geometryPath)
```


Converts [IGeometryPath](../../com.aspose.slides/igeometrypath) to android.graphics.Path. GraphicsPath can be transformed in a different ways using its convenient methods and then transformed back into the [IGeometryPath](../../com.aspose.slides/igeometrypath) to use in [GeometryShape](../../com.aspose.slides/geometryshape) via \#graphicsPathToGeometryPath(android.graphics.Path).graphicsPathToGeometryPath(android.graphics.Path) method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| geometryPath | [IGeometryPath](../../com.aspose.slides/igeometrypath) | -------------------- |

**Returns:**
android.graphics.Path - Shape path
