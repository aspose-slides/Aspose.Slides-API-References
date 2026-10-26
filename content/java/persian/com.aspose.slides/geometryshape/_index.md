---
title: GeometryShape
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایندهٔ کلاس والد برای تمام اشکال هندسی است.
type: docs
url: /fa/com.aspose.slides/geometryshape/
---
**وراثت:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**تمام رابط‌های پیاده‌سازی شده:**  
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)  
```
public abstract class GeometryShape extends Shape implements IGeometryShape
```

نمایانگر کلاس والد برای تمام اشکال هندسی است.

## متدها

| Method | Description |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | کپی مسیر شکل هندسی را بازمی‌گرداند. |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | ژئومتری شکل را از شیء [IGeometryPath](../../com.aspose.slides/igeometrypath) به‌روزرسانی می‌کند. |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | ژئومتری شکل را از آرایه‌ای از [IGeometryPath](../../com.aspose.slides/igeometrypath) به‌روزرسانی می‌کند. |
| [getShapeStyle()](#getShapeStyle--) | شیء سبک شکل را بازمی‌گرداند. |
| [getShapeType()](#getShapeType--) | نوع پیش‌تنظیم ژئومتری را بازمی‌گرداند یا تنظیم می‌کند. |
| [setShapeType(int value)](#setShapeType-int-) | نوع پیش‌تنظیم ژئومتری را بازمی‌گرداند یا تنظیم می‌کند. |
| [getAdjustments()](#getAdjustments--) | مجموعه‌ای از مقادیر تنظیم شکل را بازمی‌گرداند. |
| [createShapeElements()](#createShapeElements--) | آرایه‌ای از عناصر شکل را ایجاد و بازمی‌گرداند. |

### getGeometryPaths() {#getGeometryPaths--}
```
public final IGeometryPath[] getGeometryPaths()
```

کپی مسیر شکل هندسی را بازمی‌گرداند. مختصات نسبت به گوشهٔ بالای-چپ شکل است.

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

**بازمی‌گرداند:**  
com.aspose.slides.IGeometryPath[] - Array of [IGeometryPath](../../com.aspose.slides/igeometrypath)

### setGeometryPath(IGeometryPath geometryPath) {#setGeometryPath-com.aspose.slides.IGeometryPath-}
```
public final void setGeometryPath(IGeometryPath geometryPath)
```

ژئومتری شکل را از شیء [IGeometryPath](../../com.aspose.slides/igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالای-چپ شکل باشد. نوع شکل را (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) به [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom) تغییر می‌دهد.

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
| geometryPath | [IGeometryPath](../../com.aspose.slides/igeometrypath) | مسیر هندسه |

### setGeometryPaths(IGeometryPath[] geometryPaths) {#setGeometryPaths-com.aspose.slides.IGeometryPath---}
```
public final void setGeometryPaths(IGeometryPath[] geometryPaths)
```

ژئومتری شکل را از آرایه‌ای از [IGeometryPath](../../com.aspose.slides/igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالای-چپ شکل باشد. نوع شکل را (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) به [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom) تغییر می‌دهد.

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
| geometryPaths | [IGeometryPath\[\]](../../com.aspose.slides/igeometrypath) | آرایهٔ مسیرهای هندسه |

### getShapeStyle() {#getShapeStyle--}
```
public final IShapeStyle getShapeStyle()
```

شیء سبک شکل را بازمی‌گرداند. فقط‌خواندنی [IShapeStyle](../../com.aspose.slides/ishapestyle).

**بازمی‌گرداند:**  
[IShapeStyle](../../com.aspose.slides/ishapestyle)

### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

نوع پیش‌تنظیم ژئومتری را بازمی‌گرداند یا تنظیم می‌کند. نکته: با تغییر مقدار، تمام مقادیر تنظیم به مقادیر پیش‌فرض خود بازنشانی می‌شوند. خواندنی/نوشتنی [ShapeType](../../com.aspose.slides/shapetype).

**بازمی‌گرداند:**  
int

### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

نوع پیش‌تنظیم ژئومتری را بازمی‌گرداند یا تنظیم می‌کند. نکته: با تغییر مقدار، تمام مقادیر تنظیم به مقادیر پیش‌فرض خود بازنشانی می‌شوند. خواندنی/نوشتنی [ShapeType](../../com.aspose.slides/shapetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getAdjustments() {#getAdjustments--}
```
public final IAdjustValueCollection getAdjustments()
```

مجموعه‌ای از مقادیر تنظیم شکل را بازمی‌گرداند. فقط‌خواندنی [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection).

**بازمی‌گرداند:**  
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)

### createShapeElements() {#createShapeElements--}
```
public final IShapeElement[] createShapeElements()
```

آرایه‌ای از عناصر شکل را ایجاد و بازمی‌گرداند.

**بازمی‌گرداند:**  
com.aspose.slides.IShapeElement[] - آرایه‌ای از [ShapeElement](../../com.aspose.slides/shapeelement)