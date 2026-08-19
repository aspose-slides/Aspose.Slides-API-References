---
title: IGeometryShape
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایندهٔ کلاس والد برای تمام شکل‌های هندسی است.
type: docs
url: /fa/com.aspose.slides/igeometryshape/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape)
```
public interface IGeometryShape extends IShape
```

نمایانگر کلاس والد برای تمام اشکال هندسی است.
## متدها

| متد | توضیح |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | کپی مسیر شکل هندسی را برمی‌گرداند. |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | هندسه شکل را از شی [IGeometryPath](../../com.aspose.slides/igeometrypath) بروزرسانی می‌کند. |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | هندسه شکل را از آرایه‌ای از [IGeometryPath](../../com.aspose.slides/igeometrypath) بروزرسانی می‌کند. |
| [getShapeStyle()](#getShapeStyle--) | شیء سبک شکل را برمی‌گرداند. |
| [getShapeType()](#getShapeType--) | نوع پیش‌تنظیم هندسه را برمی‌گرداند یا تنظیم می‌کند. |
| [setShapeType(int value)](#setShapeType-int-) | نوع پیش‌تنظیم هندسه را برمی‌گرداند یا تنظیم می‌کند. |
| [getAdjustments()](#getAdjustments--) | مجموعه‌ای از مقادیر تنظیم شکل را برمی‌گرداند. |
| [createShapeElements()](#createShapeElements--) | آرایه‌ای از عناصر شکل را ایجاد و برمی‌گرداند. |
### getGeometryPaths() {#getGeometryPaths--}
```
public abstract IGeometryPath[] getGeometryPaths()
```

کپی مسیر شکل هندسی را برمی‌گرداند. مختصات نسبت به گوشهٔ بالا-چپ شکل نسبی هستند.

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

**بازگشت:**
com.aspose.slides.IGeometryPath[] - آرایه‌ای از [IGeometryPath](../../com.aspose.slides/igeometrypath)
### setGeometryPath(IGeometryPath geometryPath) {#setGeometryPath-com.aspose.slides.IGeometryPath-}
```
public abstract void setGeometryPath(IGeometryPath geometryPath)
```

هندسه شکل را از شی [IGeometryPath](../../com.aspose.slides/igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالا-چپ شکل باشند. نوع شکل را (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) به [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom) تغییر می‌دهد.

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

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| geometryPath | [IGeometryPath](../../com.aspose.slides/igeometrypath) | مسیر هندسی |

### setGeometryPaths(IGeometryPath[] geometryPaths) {#setGeometryPaths-com.aspose.slides.IGeometryPath---}
```
public abstract void setGeometryPaths(IGeometryPath[] geometryPaths)
```

هندسه شکل را از آرایه‌ای از [IGeometryPath](../../com.aspose.slides/igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالا-چپ شکل باشند. نوع شکل را (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) به [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom) تغییر می‌دهد.

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

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| geometryPaths | [IGeometryPath\[\]](../../com.aspose.slides/igeometrypath) | آرایه‌ای از مسیرهای هندسی |

### getShapeStyle() {#getShapeStyle--}
```
public abstract IShapeStyle getShapeStyle()
```

شیء سبک شکل را برمی‌گرداند. فقط-خواندنی [IShapeStyle](../../com.aspose.slides/ishapestyle).

**بازگشت:**
[IShapeStyle](../../com.aspose.slides/ishapestyle)
### getShapeType() {#getShapeType--}
```
public abstract int getShapeType()
```

نوع پیش‌تنظیم هندسه را برمی‌گرداند یا تنظیم می‌کند. توجه: با تغییر مقدار، همهٔ مقادیر تنظیم به مقادیر پیش‌فرض خود بازنشانی می‌شوند. خواند و نوشتن [ShapeType](../../com.aspose.slides/shapetype).

**بازگشت:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public abstract void setShapeType(int value)
```

نوع پیش‌تنظیم هندسه را برمی‌گرداند یا تنظیم می‌کند. توجه: با تغییر مقدار، همهٔ مقادیر تنظیم به مقادیر پیش‌فرض خود بازنشانی می‌شوند. خواند و نوشتن [ShapeType](../../com.aspose.slides/shapetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getAdjustments() {#getAdjustments--}
```
public abstract IAdjustValueCollection getAdjustments()
```

مجموعه‌ای از مقادیر تنظیم شکل را برمی‌گرداند. فقط-خواندنی [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection).

**بازگشت:**
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
### createShapeElements() {#createShapeElements--}
```
public abstract IShapeElement[] createShapeElements()
```

آرایه‌ای از عناصر شکل را ایجاد و برمی‌گرداند.

**بازگشت:**
com.aspose.slides.IShapeElement[] - آرایه‌ای از [IShapeElement](../../com.aspose.slides/ishapeelement)