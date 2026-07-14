---
title: IGeometryShape
second_title: Aspose.Slides لأندرويد عبر مرجع API جافا
description: يمثل الفئة الأساسية لجميع الأشكال الهندسية.
type: docs
url: /ar/com.aspose.slides/igeometryshape/
---
**جميع الواجهات المُنفذة:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape)
```
public interface IGeometryShape extends IShape
```

يمثل الفئة الأساسية لجميع الأشكال الهندسية.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | يعيد نسخة من مسار الشكل الهندسي. |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | يحدث هندسة الشكل من كائن [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | يحدث هندسة الشكل من مصفوفة [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [getShapeStyle()](#getShapeStyle--) | يعيد كائن نمط الشكل. |
| [getShapeType()](#getShapeType--) | يعيد أو يضبط نوع الشكل الهندسي المحدد مسبقًا. |
| [setShapeType(int value)](#setShapeType-int-) | يعيد أو يضبط نوع الشكل الهندسي المحدد مسبقًا. |
| [getAdjustments()](#getAdjustments--) | يعيد مجموعة من قيم ضبط الشكل. |
| [createShapeElements()](#createShapeElements--) | ينشئ ويعيد مصفوفة من عناصر الشكل. |
### getGeometryPaths() {#getGeometryPaths--}
```
public abstract IGeometryPath[] getGeometryPaths()
```


يعيد نسخة من مسار الشكل الهندسي. الإحداثيات نسبة إلى الزاوية اليسرى العليا للشكل.

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

**القيمة المرجعة:**  
com.aspose.slides.IGeometryPath[] - مصفوفة من [IGeometryPath](../../com.aspose.slides/igeometrypath)
### setGeometryPath(IGeometryPath geometryPath) {#setGeometryPath-com.aspose.slides.IGeometryPath-}
```
public abstract void setGeometryPath(IGeometryPath geometryPath)
```


يُحدّث هندسة الشكل من كائن [IGeometryPath](../../com.aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبة إلى الزاوية اليسرى العليا للشكل. يغيّر نوع الشكل (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) إلى [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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
| المعامل | النوع | الوصف |
| --- | --- | --- |
| geometryPath | [IGeometryPath](../../com.aspose.slides/igeometrypath) | مسار الشكل الهندسي |

### setGeometryPaths(IGeometryPath[] geometryPaths) {#setGeometryPaths-com.aspose.slides.IGeometryPath---}
```
public abstract void setGeometryPaths(IGeometryPath[] geometryPaths)
```


يُحدّث هندسة الشكل من مصفوفة [IGeometryPath](../../com.aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبة إلى الزاوية اليسرى العليا للشكل. يغيّر نوع الشكل (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) إلى [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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
| المعامل | النوع | الوصف |
| --- | --- | --- |
| geometryPaths | [IGeometryPath\[\]](../../com.aspose.slides/igeometrypath) | مصفوفة مسارات الشكل الهندسي |

### getShapeStyle() {#getShapeStyle--}
```
public abstract IShapeStyle getShapeStyle()
```


يعيد كائن نمط الشكل. للقراءة فقط [IShapeStyle](../../com.aspose.slides/ishapestyle).

**القيمة المرجعة:**  
[IShapeStyle](../../com.aspose.slides/ishapestyle)
### getShapeType() {#getShapeType--}
```
public abstract int getShapeType()
```


يعيد أو يضبط نوع الشكل الهندسي المحدد مسبقًا. ملاحظة: عند تغيير القيمة سيتم إعادة جميع قيم الضبط إلى القيم الافتراضية. قابل للقراءة والكتابة [ShapeType](../../com.aspose.slides/shapetype).

**القيمة المرجعة:**  
int
### setShapeType(int value) {#setShapeType-int-}
```
public abstract void setShapeType(int value)
```


يعيد أو يضبط نوع الشكل الهندسي المحدد مسبقًا. ملاحظة: عند تغيير القيمة سيتم إعادة جميع قيم الضبط إلى القيم الافتراضية. قابل للقراءة والكتابة [ShapeType](../../com.aspose.slides/shapetype).

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getAdjustments() {#getAdjustments--}
```
public abstract IAdjustValueCollection getAdjustments()
```


يعيد مجموعة من قيم ضبط الشكل. للقراءة فقط [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection).

**القيمة المرجعة:**  
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
### createShapeElements() {#createShapeElements--}
```
public abstract IShapeElement[] createShapeElements()
```


ينشئ ويعيد مصفوفة من عناصر الشكل.

**القيمة المرجعة:**  
com.aspose.slides.IShapeElement[] - مصفوفة من [IShapeElement](../../com.aspose.slides/ishapeelement)