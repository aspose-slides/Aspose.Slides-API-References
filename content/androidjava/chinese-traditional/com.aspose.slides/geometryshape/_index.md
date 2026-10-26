---
title: GeometryShape
second_title: Aspose.Slides for Android via Java API 參考
description: 表示所有幾何形狀的父類別。
type: docs
url: /zh-hant/com.aspose.slides/geometryshape/
---
**繼承:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**已實作的介面:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public abstract class GeometryShape extends Shape implements IGeometryShape
```

表示所有幾何形狀的父類別。
## 方法

| Method | Description |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | 返回幾何形狀路徑的副本。 |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | 根據 [IGeometryPath](../../com.aspose.slides/igeometrypath) 物件更新形狀的幾何。 |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | 根據 [IGeometryPath](../../com.aspose.slides/igeometrypath) 陣列更新形狀的幾何。 |
| [getShapeStyle()](#getShapeStyle--) | 返回形狀的樣式物件。 |
| [getShapeType()](#getShapeType--) | 返回或設定幾何預設類型。 |
| [setShapeType(int value)](#setShapeType-int-) | 返回或設定幾何預設類型。 |
| [getAdjustments()](#getAdjustments--) | 返回形狀調整值的集合。 |
| [createShapeElements()](#createShapeElements--) | 建立並返回形狀元素的陣列。 |
### getGeometryPaths() {#getGeometryPaths--}
```
public final IGeometryPath[] getGeometryPaths()
```

返回幾何形狀路徑的副本。座標相對於形狀的左上角。

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

**傳回值:**
com.aspose.slides.IGeometryPath[] - [IGeometryPath](../../com.aspose.slides/igeometrypath) 陣列
### setGeometryPath(IGeometryPath geometryPath) {#setGeometryPath-com.aspose.slides.IGeometryPath-}
```
public final void setGeometryPath(IGeometryPath geometryPath)
```

根據 [IGeometryPath](../../com.aspose.slides/igeometrypath) 物件更新形狀的幾何。座標必須相對於形狀的左上角。將形狀的類型 (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) 變更為 [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom)。

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

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| geometryPath | [IGeometryPath](../../com.aspose.slides/igeometrypath) | 幾何路徑 |
### setGeometryPaths(IGeometryPath[] geometryPaths) {#setGeometryPaths-com.aspose.slides.IGeometryPath---}
```
public final void setGeometryPaths(IGeometryPath[] geometryPaths)
```

根據 [IGeometryPath](../../com.aspose.slides/igeometrypath) 陣列更新形狀的幾何。座標必須相對於形狀的左上角。將形狀的類型 (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) 變更為 [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom)。

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

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| geometryPaths | [IGeometryPath\[\]](../../com.aspose.slides/igeometrypath) | 幾何路徑陣列 |
### getShapeStyle() {#getShapeStyle--}
```
public final IShapeStyle getShapeStyle()
```

返回形狀的樣式物件。唯讀 [IShapeStyle](../../com.aspose.slides/ishapestyle)。

**傳回值:**
[IShapeStyle](../../com.aspose.slides/ishapestyle)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

返回或設定幾何預設類型。備註：值變更時，所有調整值將重置為預設值。讀寫 [ShapeType](../../com.aspose.slides/shapetype)。

**傳回值:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

返回或設定幾何預設類型。備註：值變更時，所有調整值將重置為預設值。讀寫 [ShapeType](../../com.aspose.slides/shapetype)。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getAdjustments() {#getAdjustments--}
```
public final IAdjustValueCollection getAdjustments()
```

返回形狀調整值的集合。唯讀 [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)。

**傳回值:**
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
### createShapeElements() {#createShapeElements--}
```
public final IShapeElement[] createShapeElements()
```

建立並返回形狀元素的陣列。

**傳回值:**
com.aspose.slides.IShapeElement[] - [ShapeElement](../../com.aspose.slides/shapeelement) 陣列