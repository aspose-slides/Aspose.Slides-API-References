---
title: GeometryShape
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایان‌گر کلاس والد برای تمام اشکال هندسی است.
type: docs
url: /fa/com.aspose.slides/geometryshape/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public abstract class GeometryShape extends Shape implements IGeometryShape
```

کلاس والد برای تمام اشکال هندسی را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | یک کپی از مسیر شکل هندسی را برمی‌گرداند. |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | شکل هندسی را از شیء [IGeometryPath](../../com.aspose.slides/igeometrypath) به‌روزرسانی می‌کند. |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | شکل هندسی را از آرایه‌ای از [IGeometryPath](../../com.aspose.slides/igeometrypath) به‌روزرسانی می‌کند. |
| [getShapeStyle()](#getShapeStyle--) | یک شیء سبک شکل را برمی‌گرداند. |
| [getShapeType()](#getShapeType--) | نوع پیش‌تنظیم هندسه را برمی‌گرداند یا تنظیم می‌کند. |
| [setShapeType(int value)](#setShapeType-int-) | نوع پیش‌تنظیم هندسه را برمی‌گرداند یا تنظیم می‌کند. |
| [getAdjustments()](#getAdjustments--) | یک مجموعه از مقادیر تنظیم شکل را برمی‌گرداند. |
| [createShapeElements()](#createShapeElements--) | آرایه‌ای از عناصر شکل را ایجاد و برمی‌گرداند. |
### getGeometryPaths() {#getGeometryPaths--}
```
public final IGeometryPath[] getGeometryPaths()
```

یک کپی از مسیر شکل هندسی را برمی‌گرداند. مختصات نسبت به گوشهٔ بالا سمت چپ شکل هستند.

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

**بازگرداندن:**
com.aspose.slides.IGeometryPath[] - آرایه‌ای از [IGeometryPath](../../com.aspose.slides/igeometrypath)
### setGeometryPath(IGeometryPath geometryPath) {#setGeometryPath-com.aspose.slides.IGeometryPath-}
```
public final void setGeometryPath(IGeometryPath geometryPath)
```

شکل هندسی را از شیء [IGeometryPath](../../com.aspose.slides/igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالا سمت چپ شکل باشد. نوع شکل را (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) به [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom) تغییر می‌دهد.

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
public final void setGeometryPaths(IGeometryPath[] geometryPaths)
```

شکل هندسی را از آرایه‌ای از [IGeometryPath](../../com.aspose.slides/igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالا سمت چپ شکل باشد. نوع شکل را (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) به [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom) تغییر می‌دهد.

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
public final IShapeStyle getShapeStyle()
```

یک شیء سبک شکل را برمی‌گرداند. فقط-خواندنی [IShapeStyle](../../com.aspose.slides/ishapestyle).

**بازگرداندن:**
[IShapeStyle](../../com.aspose.slides/ishapestyle)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

نوع پیش‌تنظیم هندسه را برمی‌گرداند یا تنظیم می‌کند. توجه: با تغییر مقدار، تمام مقادیر تنظیم به مقادیر پیش‌فرض خود بازنشانی می‌شوند. خواندنی-نوشتنی [ShapeType](../../com.aspose.slides/shapetype).

**بازگرداندن:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

نوع پیش‌تنظیم هندسه را برمی‌گرداند یا تنظیم می‌کند. توجه: با تغییر مقدار، تمام مقادیر تنظیم به مقادیر پیش‌فرض خود بازنشانی می‌شوند. خواندنی-نوشتنی [ShapeType](../../com.aspose.slides/shapetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getAdjustments() {#getAdjustments--}
```
public final IAdjustValueCollection getAdjustments()
```

یک مجموعه از مقادیر تنظیم شکل را برمی‌گرداند. فقط-خواندنی [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection).

**بازگرداندن:**
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
### createShapeElements() {#createShapeElements--}
```
public final IShapeElement[] createShapeElements()
```

آرایه‌ای از عناصر شکل را ایجاد و برمی‌گرداند.

**بازگرداندن:**
com.aspose.slides.IShapeElement[] - آرایه‌ای از [ShapeElement](../../com.aspose.slides/shapeelement)