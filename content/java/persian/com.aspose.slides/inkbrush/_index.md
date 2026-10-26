---
title: InkBrush
second_title: Aspose.Slides برای مرجع API Java
description: یک شیء inkBrush را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/inkbrush/
---
**وارثی:**
java.lang.Object

**تمام واسط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)
```
public class InkBrush implements IInkBrush
```

یک شیء inkBrush را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getColor()](#getColor--) | مقدار رنگ براش برای یک خط را دریافت یا تنظیم می‌کند. |
| [setColor(Color value)](#setColor-java.awt.Color-) | مقدار رنگ براش برای یک خط را دریافت یا تنظیم می‌کند. |
| [getSize()](#getSize--) | اندازه براش برای یک خط را به نقطه تعیین می‌کند یا دریافت می‌کند. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | اندازه براش برای یک خط را به نقطه تعیین می‌کند یا دریافت می‌کند. |
| [getInkEffect()](#getInkEffect--) | نوع اثر جوهر (مانند Galaxy، Gold، Silver) را دریافت می‌کند که سبک بصری خط جوهر را تعریف می‌کند. |
### getColor() {#getColor--}
```
public final Color getColor()
```

مقدار رنگ براش برای یک خط را دریافت یا تنظیم می‌کند.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Color brushColor = brush.getColor();
>      brush.setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگشت:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```

مقدار رنگ براش برای یک خط را دریافت یا تنظیم می‌کند.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Color brushColor = brush.getColor();
>      brush.setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.awt.Color |  |

### getSize() {#getSize--}
```
public final Dimension2D getSize()
```

اندازه براش برای یک خط را به نقطه تعیین می‌کند یا دریافت می‌کند.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Dimension2D brushSize = brush.getSize();
>      brush.setSize(new Dimension(5, 10));
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگشت:**
java.awt.geom.Dimension2D
### setSize(Dimension2D value) {#setSize-java.awt.geom.Dimension2D-}
```
public final void setSize(Dimension2D value)
```

اندازه براش برای یک خط را به نقطه تعیین می‌کند یا دریافت می‌کند.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Dimension2D brushSize = brush.getSize();
>      brush.setSize(new Dimension(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.awt.geom.Dimension2D |  |

### getInkEffect() {#getInkEffect--}
```
public final int getInkEffect()
```

نوع اثر جوهر (مانند Galaxy، Gold، Silver) را دریافت می‌کند که سبک بصری خط جوهر را تعریف می‌کند. مقدار از ویژگی براش "inkEffects" تجزیه می‌شود. اگر هیچ اثر شناخته‌شده‌ای مشخص نشده باشد، [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) بازگردانده می‌شود.

**بازگشت:**
int