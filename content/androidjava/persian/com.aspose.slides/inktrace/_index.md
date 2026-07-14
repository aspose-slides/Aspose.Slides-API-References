---
title: InkTrace
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: شی Trace را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/inktrace/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)
```
public class InkTrace implements IInkTrace
```

نماد یک شی Trace است. یک عنصر Trace برای ضبط داده‌های به‌دست آمده توسط دیجیتایزر استفاده می‌شود. این شامل یک دنباله از نقاط است که بر اساس مشخصات ارائه شده توسط شی InkTraceFormat کدگذاری شده‌اند.

## متدها

| متد | توضیح |
| --- | --- |
| [getBrush()](#getBrush--) | Brush را برای IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) دریافت می‌کند فقط-خواندنی. |
| [getPoints()](#getPoints--) | نقاط را برای IInkLine android.graphics.PointF دریافت می‌کند فقط-خواندنی. |

### getBrush() {#getBrush--}
```
public final IInkBrush getBrush()
```

Brush را برای IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) دریافت می‌کند فقط-خواندنی.

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

**بازمی‌گرداند:**
[IInkBrush](../../com.aspose.slides/iinkbrush)

### getPoints() {#getPoints--}
```
public final PointF[] getPoints()
```

نقاط را برای IInkLine android.graphics.PointF دریافت می‌کند فقط-خواندنی.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      android.graphics.PointF[] points = traces[0].getPoints();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازمی‌گرداند:**
android.graphics.PointF[]