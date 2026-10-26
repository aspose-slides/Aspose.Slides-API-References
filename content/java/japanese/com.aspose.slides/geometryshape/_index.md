---
title: GeometryShape
second_title: Aspose.Slides for Java API リファレンス
description: すべての幾何学的形状の親クラスを表します。
type: docs
url: /ja/com.aspose.slides/geometryshape/
---
**継承:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)  
```
public abstract class GeometryShape extends Shape implements IGeometryShape
```

すべての幾何学的形状の親クラスを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | ジオメトリ形状のパスのコピーを返します。 |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | [IGeometryPath](../../com.aspose.slides/igeometrypath) オブジェクトから形状のジオメトリを更新します。 |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | [IGeometryPath](../../com.aspose.slides/igeometrypath) の配列から形状のジオメトリを更新します。 |
| [getShapeStyle()](#getShapeStyle--) | 形状のスタイルオブジェクトを返します。 |
| [getShapeType()](#getShapeType--) | ジオメトリのプリセットタイプを取得または設定します。 |
| [setShapeType(int value)](#setShapeType-int-) | ジオメトリのプリセットタイプを取得または設定します。 |
| [getAdjustments()](#getAdjustments--) | 形状の調整値のコレクションを返します。 |
| [createShapeElements()](#createShapeElements--) | 形状の要素の配列を作成し、返します。 |
### getGeometryPaths() {#getGeometryPaths--}
```
public final IGeometryPath[] getGeometryPaths()
```

ジオメトリ形状のパスのコピーを返します。座標は形状の左上隅を基準としています。

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


**戻り値:**  
com.aspose.slides.IGeometryPath[] - [IGeometryPath](../../com.aspose.slides/igeometrypath) の配列
### setGeometryPath(IGeometryPath geometryPath) {#setGeometryPath-com.aspose.slides.IGeometryPath-}
```
public final void setGeometryPath(IGeometryPath geometryPath)
```

[IGeometryPath](../../com.aspose.slides/igeometrypath) オブジェクトから形状のジオメトリを更新します。座標は形状の左上隅を基準とする必要があります。形状のタイプ (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) を [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom) に変更します。

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


**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| geometryPath | [IGeometryPath](../../com.aspose.slides/igeometrypath) | ジオメトリパス |

### setGeometryPaths(IGeometryPath[] geometryPaths) {#setGeometryPaths-com.aspose.slides.IGeometryPath---}
```
public final void setGeometryPaths(IGeometryPath[] geometryPaths)
```

[IGeometryPath](../../com.aspose.slides/igeometrypath) の配列から形状のジオメトリを更新します。座標は形状の左上隅を基準とする必要があります。形状のタイプ (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) を [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom) に変更します。

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

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| geometryPaths | [IGeometryPath\[\]](../../com.aspose.slides/igeometrypath) | ジオメトリパスの配列 |

### getShapeStyle() {#getShapeStyle--}
```
public final IShapeStyle getShapeStyle()
```

形状のスタイルオブジェクトを返します。読み取り専用 [IShapeStyle](../../com.aspose.slides/ishapestyle)。

**戻り値:**  
[IShapeStyle](../../com.aspose.slides/ishapestyle)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

ジオメトリのプリセットタイプを取得または設定します。注: 値が変更されると、すべての調整値はデフォルト値にリセットされます。読み書き [ShapeType](../../com.aspose.slides/shapetype)。

**戻り値:**  
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

ジオメトリのプリセットタイプを取得または設定します。注: 値が変更されると、すべての調整値はデフォルト値にリセットされます。読み書き [ShapeType](../../com.aspose.slides/shapetype)。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getAdjustments() {#getAdjustments--}
```
public final IAdjustValueCollection getAdjustments()
```

形状の調整値のコレクションを返します。読み取り専用 [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)。

**戻り値:**  
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
### createShapeElements() {#createShapeElements--}
```
public final IShapeElement[] createShapeElements()
```

形状の要素の配列を作成し、返します。

**戻り値:**  
com.aspose.slides.IShapeElement[] - [ShapeElement](../../com.aspose.slides/shapeelement) の配列