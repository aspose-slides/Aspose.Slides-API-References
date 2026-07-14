---
title: IInkTrace
second_title: Aspose.Slides برای Android از طریق Java مرجع API
description: نمایانگر خط دست‌نوشته در یک شیء Ink.
type: docs
url: /fa/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

نمایانگر خط دست‌نوشته در یک شیء Ink.
## متدها

| متد | توضیح |
| --- | --- |
| [getBrush()](#getBrush--) | دریافت Brush برای IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) فقط خواندنی. |
| [getPoints()](#getPoints--) | دریافت نقاط برای IInkLine android.graphics.PointF فقط خواندنی. |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```


دریافت Brush برای IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) فقط خواندنی.

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
public abstract PointF[] getPoints()
```


دریافت نقاط برای IInkLine android.graphics.PointF فقط خواندنی.

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