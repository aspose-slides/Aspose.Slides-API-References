---
title: GeometryShape
second_title: Aspose.Slides لـ Java مرجع API
description: يمثل الفئة الأصلية لجميع الأشكال الهندسية.
type: docs
url: /ar/com.aspose.slides/geometryshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**All Implemented Interfaces:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public abstract class GeometryShape extends Shape implements IGeometryShape
```

يمثل الفئة الأصلية لجميع الأشكال الهندسية.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | يعيد نسخة من مسار الشكل الهندسي. |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | يقوم بتحديث هندسة الشكل من كائن [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | يقوم بتحديث هندسة الشكل من مصفوفة من [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [getShapeStyle()](#getShapeStyle--) | يعيد كائن نمط الشكل. |
| [getShapeType()](#getShapeType--) | يعيد أو يضبط نوع الإعداد المسبق للهندسة. |
| [setShapeType(int value)](#setShapeType-int-) | يعيد أو يضبط نوع الإعداد المسبق للهندسة. |
| [getAdjustments()](#getAdjustments--) | يعيد مجموعة من قيم تعديل الشكل. |
| [createShapeElements()](#createShapeElements--) | ينشئ ويعيد مصفوفة من عناصر الشكل. |
### getGeometryPaths() {#getGeometryPaths--}
```
public final IGeometryPath[] getGeometryPaths()
```


يعيد نسخة من مسار الشكل الهندسي. الإحداثيات نسبية إلى الزاوية العليا اليسرى للشكل.

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


يقوم بتحديث هندسة الشكل من كائن [IGeometryPath](../../com.aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبية إلى الزاوية العليا اليسرى للشكل. يغيّر نوع الشكل (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) إلى [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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


**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| geometryPath | [IGeometryPath](../../com.aspose.slides/igeometrypath) | مسار الهندسة |

### setGeometryPaths(IGeometryPath[] geometryPaths) {#setGeometryPaths-com.aspose.slides.IGeometryPath---}
```
public final void setGeometryPaths(IGeometryPath[] geometryPaths)
```


يقوم بتحديث هندسة الشكل من مصفوفة من [IGeometryPath](../../com.aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبية إلى الزاوية العليا اليسرى للشكل. يغيّر نوع الشكل (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) إلى [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| geometryPaths | [IGeometryPath\[\]](../../com.aspose.slides/igeometrypath) | مصفوفة من مسارات الهندسة |

### getShapeStyle() {#getShapeStyle--}
```
public final IShapeStyle getShapeStyle()
```


يعيد كائن نمط الشكل. للقراءة فقط [IShapeStyle](../../com.aspose.slides/ishapestyle).

**الإرجاع:**
[IShapeStyle](../../com.aspose.slides/ishapestyle)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


يعيد أو يضبط نوع الإعداد المسبق للهندسة. ملاحظة: عند تغيير القيمة ستُعاد جميع قيم التعديل إلى القيم الافتراضية الخاصة بها. للقراءة والكتابة [ShapeType](../../com.aspose.slides/shapetype).

**الإرجاع:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


يعيد أو يضبط نوع الإعداد المسبق للهندسة. ملاحظة: عند تغيير القيمة ستُعاد جميع قيم التعديل إلى القيم الافتراضية الخاصة بها. للقراءة والكتابة [ShapeType](../../com.aspose.slides/shapetype).

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getAdjustments() {#getAdjustments--}
```
public final IAdjustValueCollection getAdjustments()
```


يعيد مجموعة من قيم تعديل الشكل. للقراءة فقط [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection).

**الإرجاع:**
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
### createShapeElements() {#createShapeElements--}
```
public final IShapeElement[] createShapeElements()
```


ينشئ ويعيد مصفوفة من عناصر الشكل.

**الإرجاع:**
com.aspose.slides.IShapeElement[] - مصفوفة من [ShapeElement](../../com.aspose.slides/shapeelement)