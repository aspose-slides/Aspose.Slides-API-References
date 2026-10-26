---
title: IGeometryShape
second_title: Aspose.Slides for Android via Java API 参考
description: 表示所有几何形状的父类。
type: docs
url: /zh/com.aspose.slides/igeometryshape/
---
**All Implemented Interfaces:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape)
```
public interface IGeometryShape extends IShape
```

表示所有几何形状的父类。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | 返回几何形状路径的副本。 |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | 从 [IGeometryPath](../../com.aspose.slides/igeometrypath) 对象更新形状几何。 |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | 从 [IGeometryPath](../../com.aspose.slides/igeometrypath) 数组更新形状几何。 |
| [getShapeStyle()](#getShapeStyle--) | 返回形状的样式对象。 |
| [getShapeType()](#getShapeType--) | 返回或设置几何预设类型。 |
| [setShapeType(int value)](#setShapeType-int-) | 返回或设置几何预设类型。 |
| [getAdjustments()](#getAdjustments--) | 返回形状的调整值集合。 |
| [createShapeElements()](#createShapeElements--) | 创建并返回形状元素的数组。 |
### getGeometryPaths() {#getGeometryPaths--}
```
public abstract IGeometryPath[] getGeometryPaths()
```

返回几何形状路径的副本。坐标相对于形状的左上角。

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
public abstract void setGeometryPath(IGeometryPath geometryPath)
```

Updates shape geometry from [IGeometryPath](../../com.aspose.slides/igeometrypath) object. Coordinates must be relative to the left top corner of the shape. Changes the type of the shape (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) to [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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
public abstract void setGeometryPaths(IGeometryPath[] geometryPaths)
```

Updates shape geometry from array of [IGeometryPath](../../com.aspose.slides/igeometrypath). Coordinates must be relative to the left top corner of the shape. Changes the type of the shape (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) to [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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
| geometryPaths | [IGeometryPath\[\]](../../com.aspose.slides/igeometrypath) | Array geometry paths |

### getShapeStyle() {#getShapeStyle--}
```
public abstract IShapeStyle getShapeStyle()
```

Returns shape's style object. Read-only [IShapeStyle](../../com.aspose.slides/ishapestyle).

**Returns:**
[IShapeStyle](../../com.aspose.slides/ishapestyle)
### getShapeType() {#getShapeType--}
```
public abstract int getShapeType()
```

Returns or sets the geometry preset type. Note: on value changing all adjustment values will reset to their default values. Read/write [ShapeType](../../com.aspose.slides/shapetype).

**Returns:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public abstract void setShapeType(int value)
```

Returns or sets the geometry preset type. Note: on value changing all adjustment values will reset to their default values. Read/write [ShapeType](../../com.aspose.slides/shapetype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAdjustments() {#getAdjustments--}
```
public abstract IAdjustValueCollection getAdjustments()
```

Returns a collection of shape's adjustment values. Read-only [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection).

**Returns:**
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
### createShapeElements() {#createShapeElements--}
```
public abstract IShapeElement[] createShapeElements()

创建并返回形状元素的数组。

**返回:**  
com.aspose.slides.IShapeElement[] - 数组 [IShapeElement](../../com.aspose.slides/ishapeelement)