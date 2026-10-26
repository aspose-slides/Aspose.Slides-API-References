---
title: IInkTrace
second_title: Aspose.Slides for Java API Reference
description: نمایش خط دست‌نویس در یک شیء Ink.
type: docs
url: /fa/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

نمایش خط دست‌نویس در یک شیء Ink.
## متدها

| متد | توضیح |
| --- | --- |
| [getBrush()](#getBrush--) | Brush را برای IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) دریافت می‌کند. Read-only. |
| [getPoints()](#getPoints--) | نقاط را برای IInkLine java.awt.geom.Point2D.Float دریافت می‌کند. Read-only. |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```


Brush را برای IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) دریافت می‌کند. Read-only.

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
public abstract Point2D.Float[] getPoints()
```


نقاط را برای IInkLine java.awt.geom.Point2D.Float دریافت می‌کند. Read-only.

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