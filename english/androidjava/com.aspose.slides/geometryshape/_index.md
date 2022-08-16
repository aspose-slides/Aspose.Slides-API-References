---
title: GeometryShape
second_title: Aspose.Slides for Android via Java API Reference
description:  Represents the parent class for all geometric shapes.
type: docs
weight: 218
url: /androidjava/com.aspose.slides/geometryshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**All Implemented Interfaces:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public abstract class GeometryShape extends Shape implements IGeometryShape
```

Represents the parent class for all geometric shapes.
## Methods

| Method | Description |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | Returns the copy of path of the geometry shape. |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | Updates shape geometry from [IGeometryPath](../../com.aspose.slides/igeometrypath) object. |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | Updates shape geometry from array of [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [getShapeStyle()](#getShapeStyle--) | Returns shape's style object. |
| [getShapeType()](#getShapeType--) | Returns or sets the geometry preset type. |
| [setShapeType(int value)](#setShapeType-int-) | Returns or sets the geometry preset type. |
| [getAdjustments()](#getAdjustments--) | Returns a collection of shape's adjustment values. |
| [createShapeElements()](#createShapeElements--) | Creates and returns array of shape's elements. |
### getGeometryPaths() {#getGeometryPaths--}
```
public final IGeometryPath[] getGeometryPaths()
```


Returns the copy of path of the geometry shape. Coordinates are relative to the left top corner of the shape.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      GeometryShape shape = (GeometryShape) pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 200, 100);
>      IGeometryPath geometryPath = shape.getGeometryPaths()[0];
>      geometryPath.lineTo(100, 50, 1);
>      geometryPath.lineTo(100, 50, 4);
>      shape.setGeometryPath(geometryPath);
>      pres.save("output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
com.aspose.slides.IGeometryPath[] - Array of [IGeometryPath](../../com.aspose.slides/igeometrypath)
### setGeometryPath(IGeometryPath geometryPath) {#setGeometryPath-com.aspose.slides.IGeometryPath-}
```
public final void setGeometryPath(IGeometryPath geometryPath)
```


Updates shape geometry from [IGeometryPath](../../com.aspose.slides/igeometrypath) object. Coordinates must be relative to the left top corner of the shape. Changes the type of the shape (ShapeType(\#getShapeType/\#setShapeType(int))) to [ShapeType\#Custom](../../com.aspose.slides/shapetype\#Custom).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      GeometryShape shape = (GeometryShape) pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 200, 100);
>      GeometryPath geometryPath0 = new GeometryPath();
>      geometryPath0.moveTo(0, 0);
>      geometryPath0.lineTo(shape.getWidth(), 0);
>      geometryPath0.lineTo(shape.getWidth(), shape.getHeight()/3);
>      geometryPath0.lineTo(0, shape.getHeight() / 3);
>      geometryPath0.closeFigure();
>      GeometryPath geometryPath1 = new GeometryPath();
>      geometryPath1.moveTo(0, shape.getHeight()/3 * 2);
>      geometryPath1.lineTo(shape.getWidth(), shape.getHeight() / 3 * 2);
>      geometryPath1.lineTo(shape.getWidth(), shape.getHeight());
>      geometryPath1.lineTo(0, shape.getHeight());
>      geometryPath1.closeFigure();
>      shape.setGeometryPaths(new GeometryPath[] { geometryPath0, geometryPath1});
>      pres.save("output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| geometryPath | [IGeometryPath](../../com.aspose.slides/igeometrypath) | Geometry path |

### setGeometryPaths(IGeometryPath[] geometryPaths) {#setGeometryPaths-com.aspose.slides.IGeometryPath---}
```
public final void setGeometryPaths(IGeometryPath[] geometryPaths)
```


Updates shape geometry from array of [IGeometryPath](../../com.aspose.slides/igeometrypath). Coordinates must be relative to the left top corner of the shape. Changes the type of the shape (ShapeType(\#getShapeType/\#setShapeType(int))) to [ShapeType\#Custom](../../com.aspose.slides/shapetype\#Custom).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      GeometryShape shape = (GeometryShape)pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 200, 100);
>      IGeometryPath geometryPath = shape.getGeometryPaths()[0];
>      geometryPath.lineTo(100, 50, 1);
>      geometryPath.lineTo(100, 50, 4);
>      shape.setGeometryPath(geometryPath);
>      pres.save("output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| geometryPaths | com.aspose.slides.IGeometryPath[] | Array geometry paths |

### getShapeStyle() {#getShapeStyle--}
```
public final IShapeStyle getShapeStyle()
```


Returns shape's style object. Read-only [IShapeStyle](../../com.aspose.slides/ishapestyle).

**Returns:**
[IShapeStyle](../../com.aspose.slides/ishapestyle)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


Returns or sets the geometry preset type. Note: on value changing all adjustment values will reset to their default values. Read/write [ShapeType](../../com.aspose.slides/shapetype).

**Returns:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


Returns or sets the geometry preset type. Note: on value changing all adjustment values will reset to their default values. Read/write [ShapeType](../../com.aspose.slides/shapetype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAdjustments() {#getAdjustments--}
```
public final IAdjustValueCollection getAdjustments()
```


Returns a collection of shape's adjustment values. Read-only [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection).

**Returns:**
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
### createShapeElements() {#createShapeElements--}
```
public final IShapeElement[] createShapeElements()
```


Creates and returns array of shape's elements.

**Returns:**
com.aspose.slides.IShapeElement[] - Array of [ShapeElement](../../com.aspose.slides/shapeelement)
