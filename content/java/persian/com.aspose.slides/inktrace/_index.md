---
title: InkTrace
second_title: مرجع API Aspose.Slides برای جاوا
description: یک شیء Trace را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/inktrace/
---
**وارثت:**  
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)  
```
public class InkTrace implements IInkTrace
```

یک شیء Trace را نشان می‌دهد. یک عنصر Trace برای ضبط داده‌های به دست آمده توسط دیجیتالایزر استفاده می‌شود. این شامل یک دنباله‌ای از نقاط است که طبق مشخصات ارائه شده توسط شیء InkTraceFormat کدگذاری شده‌اند.

## متدها

| Method | Description |
| --- | --- |
| [getBrush()](#getBrush--) | Brush را برای IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) فقط‌خواندنی دریافت می‌کند. |
| [getPoints()](#getPoints--) | نقاط را برای IInkLine java.awt.geom.Point2D.Float فقط‌خواندنی دریافت می‌کند. |

### getBrush() {#getBrush--}
```
public final IInkBrush getBrush()
```

Brush را برای IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) فقط‌خواندنی دریافت می‌کند.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگشت:**  
[IInkBrush](../../com.aspose.slides/iinkbrush)

### getPoints() {#getPoints--}
```
public final Point2D.Float[] getPoints()
```

نقاط را برای IInkLine java.awt.geom.Point2D.Float فقط‌خواندنی دریافت می‌کند.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      Point2D.Float[] points = traces[0].getPoints();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگشت:**  
java.awt.geom.Point2D.Float[]