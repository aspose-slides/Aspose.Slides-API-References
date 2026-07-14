---
title: GeometryShape
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يمثل الفئة الأب لجميع الأشكال الهندسية.
type: docs
url: /ar/com.aspose.slides/geometryshape/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)  
```
public abstract class GeometryShape extends Shape implements IGeometryShape
```

يمثل الفئة الأب لجميع الأشكال الهندسية.

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | إرجاع نسخة من مسار الشكل الهندسي. |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | تحدث هندسة الشكل من كائن [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | تحدث هندسة الشكل من مصفوفة من [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [getShapeStyle()](#getShapeStyle--) | إرجاع كائن نمط الشكل. |
| [getShapeType()](#getShapeType--) | إرجاع أو تعيين نوع الشكل الهندسي المسبق. |
| [setShapeType(int value)](#setShapeType-int-) | إرجاع أو تعيين نوع الشكل الهندسي المسبق. |
| [getAdjustments()](#getAdjustments--) | إرجاع مجموعة من قيم تعديل الشكل. |
| [createShapeElements()](#createShapeElements--) | إنشاء وإرجاع مصفوفة من عناصر الشكل. |

### getGeometryPaths() {#getGeometryPaths--}
```
public final IGeometryPath[] getGeometryPaths()
```

إرجاع نسخة من مسار الشكل الهندسي. الإحداثيات نسبية إلى الركن العلوي الأيسر للشكل.

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

**الإرجاع:**  
com.aspose.slides.IGeometryPath[] - مصفوفة من [IGeometryPath](../../com.aspose.slides/igeometrypath)

### setGeometryPath(IGeometryPath geometryPath) {#setGeometryPath-com.aspose.slides.IGeometryPath-}
```
public final void setGeometryPath(IGeometryPath geometryPath)
```

تحدث هندسة الشكل من كائن [IGeometryPath](../../com.aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبية إلى الركن العلوي الأيسر للشكل. تغير نوع الشكل (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) إلى [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| geometryPath | [IGeometryPath](../../com.aspose.slides/igeometrypath) | مسار الهندسة |

### setGeometryPaths(IGeometryPath[] geometryPaths) {#setGeometryPaths-com.aspose.slides.IGeometryPath---}
```
public final void setGeometryPaths(IGeometryPath[] geometryPaths)
```

تحدث هندسة الشكل من مصفوفة من [IGeometryPath](../../com.aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبية إلى الركن العلوي الأيسر للشكل. تغير نوع الشكل (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) إلى [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| geometryPaths | [IGeometryPath\[\]](../../com.aspose.slides/igeometrypath) | مصفوفة مسارات الهندسة |

### getShapeStyle() {#getShapeStyle--}
```
public final IShapeStyle getShapeStyle()
```

إرجاع كائن نمط الشكل. قراءة فقط [IShapeStyle](../../com.aspose.slides/ishapestyle).

**الإرجاع:**
[IShapeStyle](../../com.aspose.slides/ishapestyle)

### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

إرجاع أو تعيين نوع الشكل الهندسي المسبق. ملاحظة: عند تغيير القيمة سيتم إعادة تعيين جميع قيم التعديل إلى قيمها الافتراضية. قراءة/كتابة [ShapeType](../../com.aspose.slides/shapetype).

**الإرجاع:**
int

### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

إرجاع أو تعيين نوع الشكل الهندسي المسبق. ملاحظة: عند تغيير القيمة سيتم إعادة تعيين جميع قيم التعديل إلى قيمها الافتراضية. قراءة/كتابة [ShapeType](../../com.aspose.slides/shapetype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getAdjustments() {#getAdjustments--}
```
public final IAdjustValueCollection getAdjustments()
```

إرجاع مجموعة من قيم تعديل الشكل. قراءة فقط [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection).

**الإرجاع:**
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)

### createShapeElements() {#createShapeElements--}
```
public final IShapeElement[] createShapeElements()
```

ينشئ ويعيد مصفوفة من عناصر الشكل.

**الإرجاع:**
com.aspose.slides.IShapeElement[] - مصفوفة من [ShapeElement](../../com.aspose.slides/shapeelement)