---
title: IGeometryShape
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نشان‌دهنده کلاس والد برای تمام اشکال هندسی.
type: docs
url: /fa/com.aspose.slides/igeometryshape/
---
**تمام واسط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IShape](../../com.aspose.slides/ishape)
```
public interface IGeometryShape extends IShape
```

نشان‌دهنده کلاس والد برای تمام اشکال هندسی است.
## متدها

| متد | توضیح |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | یک نسخه از مسیر شکل هندسی را باز می‌گرداند. |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | هندسه شکل را از شی [IGeometryPath](../../com.aspose.slides/igeometrypath) به‌روزرسانی می‌کند. |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | هندسه شکل را از آرایه‌ای از [IGeometryPath](../../com.aspose.slides/igeometrypath) به‌روزرسانی می‌کند. |
| [getShapeStyle()](#getShapeStyle--) | شی سبک شکل را باز می‌گرداند. |
| [getShapeType()](#getShapeType--) | نوع پیش‌تنظیم هندسه را باز می‌گرداند یا تنظیم می‌کند. |
| [setShapeType(int value)](#setShapeType-int-) | نوع پیش‌تنظیم هندسه را باز می‌گرداند یا تنظیم می‌کند. |
| [getAdjustments()](#getAdjustments--) | یک مجموعه از مقادیر تنظیم شکل را باز می‌گرداند. |
| [createShapeElements()](#createShapeElements--) | یک آرایه از عناصر شکل را می‌سازد و باز می‌گرداند. |
### getGeometryPaths() {#getGeometryPaths--}
```
public abstract IGeometryPath[] getGeometryPaths()
```

یک نسخه از مسیر شکل هندسی را باز می‌گرداند. مختصات نسبت به گوشهٔ بالا-چپ شکل نسبی هستند.

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

هندسه شکل را از شی [IGeometryPath](../../com.aspose.slides/igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالا-چپ شکل باشد. نوع شکل را (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) به [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom) تغییر می‌دهد.

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

هندسه شکل را از آرایه‌ای از [IGeometryPath](../../com.aspose.slides/igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالا-چپ شکل باشد. نوع شکل را (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) به [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom) تغییر می‌دهد.

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
| geometryPaths | [IGeometryPath\[\]](../../com.aspose.slides/igeometrypath) | آرایه مسیرهای هندسی |

### getShapeStyle() {#getShapeStyle--}
```
public abstract IShapeStyle getShapeStyle()
```

شی سبک شکل را باز می‌گرداند. فقط خواندنی [IShapeStyle](../../com.aspose.slides/ishapestyle).

**بازگشت:**  
[IShapeStyle](../../com.aspose.slides/ishapestyle)
### getShapeType() {#getShapeType--}
```
public abstract int getShapeType()
```

نوع پیش‌تنظیم هندسه را باز می‌گرداند یا تنظیم می‌کند. نکته: با تغییر مقدار، تمام مقادیر تنظیم به مقادیر پیش‌فرض خود بازنشانی می‌شوند. قابل خواندن/نوشتن [ShapeType](../../com.aspose.slides/shapetype).

**بازگشت:**  
int
### setShapeType(int value) {#setShapeType-int-}
```
public abstract void setShapeType(int value)
```

نوع پیش‌تنظیم هندسه را باز می‌گرداند یا تنظیم می‌کند. نکته: با تغییر مقدار، تمام مقادیر تنظیم به مقادیر پیش‌فرض خود بازنشانی می‌شوند. قابل خواندن/نوشتن [ShapeType](../../com.aspose.slides/shapetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getAdjustments() {#getAdjustments--}
```
public abstract IAdjustValueCollection getAdjustments()
```

یک مجموعه از مقادیر تنظیم شکل را باز می‌گرداند. فقط خواندنی [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection).

**بازگشت:**  
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
### createShapeElements() {#createShapeElements--}
```
public abstract IShapeElement[] createShapeElements()
```

یک آرایه از عناصر شکل را می‌سازد و باز می‌گرداند.

**بازگشت:**  
com.aspose.slides.IShapeElement[] - آرایه‌ای از [IShapeElement](../../com.aspose.slides/ishapeelement)