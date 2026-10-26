---
title: GeometryShape
second_title: Aspose.Slides for Android via Java API Referansı
description: Tüm geometrik şekillerin üst sınıfını temsil eder.
type: docs
url: /tr/com.aspose.slides/geometryshape/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public abstract class GeometryShape extends Shape implements IGeometryShape
```

Tüm geometrik şekillerin üst sınıfını temsil eder.
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | Geometri şeklinin yolunun bir kopyasını döndürür. |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | Şeklin geometrisini [IGeometryPath](../../com.aspose.slides/igeometrypath) nesnesinden günceller. |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | Şeklin geometrisini [IGeometryPath](../../com.aspose.slides/igeometrypath) dizisinden günceller. |
| [getShapeStyle()](#getShapeStyle--) | Şeklin stil nesnesini döndürür. |
| [getShapeType()](#getShapeType--) | Geometri ön ayar türünü döndürür veya ayarlar. |
| [setShapeType(int value)](#setShapeType-int-) | Geometri ön ayar türünü döndürür veya ayarlar. |
| [getAdjustments()](#getAdjustments--) | Şeklin ayar değerlerinin bir koleksiyonunu döndürür. |
| [createShapeElements()](#createShapeElements--) | Şeklin öğelerinin bir dizisini oluşturur ve döndürür. |
### getGeometryPaths() {#getGeometryPaths--}
```
public final IGeometryPath[] getGeometryPaths()
```

Geometri şeklinin yolunun bir kopyasını döndürür. Koordinatlar şeklin sol üst köşesine göre görecelidir.

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

**Döndürür:**
com.aspose.slides.IGeometryPath[] - [IGeometryPath](../../com.aspose.slides/igeometrypath) dizisi
### setGeometryPath(IGeometryPath geometryPath) {#setGeometryPath-com.aspose.slides.IGeometryPath-}
```
public final void setGeometryPath(IGeometryPath geometryPath)
```

Şeklin geometrisini [IGeometryPath](../../com.aspose.slides/igeometrypath) nesnesinden günceller. Koordinatlar şeklin sol üst köşesine göre göreceli olmalıdır. Şeklin tipini (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom) olarak değiştirir.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| geometryPath | [IGeometryPath](../../com.aspose.slides/igeometrypath) | Geometri yolu |

### setGeometryPaths(IGeometryPath[] geometryPaths) {#setGeometryPaths-com.aspose.slides.IGeometryPath---}
```
public final void setGeometryPaths(IGeometryPath[] geometryPaths)
```

Şeklin geometrisini [IGeometryPath](../../com.aspose.slides/igeometrypath) dizisinden günceller. Koordinatlar şeklin sol üst köşesine göre göreceli olmalıdır. Şeklin tipini (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom) olarak değiştirir.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| geometryPaths | [IGeometryPath\[\]](../../com.aspose.slides/igeometrypath) | Geometri yolu dizisi |

### getShapeStyle() {#getShapeStyle--}
```
public final IShapeStyle getShapeStyle()
```

Şeklin stil nesnesini döndürür. Salt okunur [IShapeStyle](../../com.aspose.slides/ishapestyle).

**Döndürür:**
[IShapeStyle](../../com.aspose.slides/ishapestyle)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

Geometri ön ayar türünü döndürür veya ayarlar. Not: değer değiştiğinde tüm ayar değerleri varsayılan değerlerine sıfırlanır. Okunabilir/yazılabilir [ShapeType](../../com.aspose.slides/shapetype).

**Döndürür:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

Geometri ön ayar türünü döndürür veya ayarlar. Not: değer değiştiğinde tüm ayar değerleri varsayılan değerlerine sıfırlanır. Okunabilir/yazılabilir [ShapeType](../../com.aspose.slides/shapetype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getAdjustments() {#getAdjustments--}
```
public final IAdjustValueCollection getAdjustments()
```

Şeklin ayar değerlerinin bir koleksiyonunu döndürür. Salt okunur [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection).

**Döndürür:**
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
### createShapeElements() {#createShapeElements--}
```
public final IShapeElement[] createShapeElements()
```

Şeklin öğelerinin bir dizisini oluşturur ve döndürür.

**Döndürür:**
com.aspose.slides.IShapeElement[] - [ShapeElement](../../com.aspose.slides/shapeelement) dizisi