---
title: InkBrush
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر یک شیء inkBrush.
type: docs
url: /fa/com.aspose.slides/inkbrush/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)
```
public class InkBrush implements IInkBrush
```

نمایانگر یک شیء inkBrush.
## متدها

| متد | توضیح |
| --- | --- |
| [getColor()](#getColor--) | رنگ قلم‌مو را برای یک خط دریافت یا تنظیم می‌کند. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | رنگ قلم‌مو را برای یک خط دریافت یا تنظیم می‌کند. |
| [getSize()](#getSize--) | اندازه قلم‌مو را برای یک خط بر حسب نقطه دریافت یا تنظیم می‌کند. |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | اندازه قلم‌مو را برای یک خط بر حسب نقطه دریافت یا تنظیم می‌کند. |
| [getInkEffect()](#getInkEffect--) | نوع اثر جوهر (مثلاً Galaxy، Gold، Silver) را که سبک بصری خط جوهر را تعریف می‌کند، دریافت می‌کند. |

### getColor() {#getColor--}
```
public final Integer getColor()
```

رنگ قلم‌مو را برای یک خط دریافت یا تنظیم می‌کند.

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

**بازگرداندن:**
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public final void setColor(Integer value)
```

رنگ قلم‌مو را برای یک خط دریافت یا تنظیم می‌کند.

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
| value | java.lang.Integer |  |

### getSize() {#getSize--}
```
public final SizeF getSize()
```

اندازه قلم‌مو را برای یک خط بر حسب نقطه دریافت یا تنظیم می‌کند.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      SizeF brushSize = brush.getSize();
>      brush.setSize(new com.aspose.slides.android.Size(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگرداندن:**
[SizeF](../../com.aspose.slides.android/sizef)
### setSize(SizeF value) {#setSize-com.aspose.slides.android.SizeF-}
```
public final void setSize(SizeF value)
```

اندازه قلم‌مو را برای یک خط بر حسب نقطه دریافت یا تنظیم می‌کند.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      SizeF brushSize = brush.getSize();
>      brush.setSize(new com.aspose.slides.android.Size(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.slides.android/sizef) |  |

### getInkEffect() {#getInkEffect--}
```
public final int getInkEffect()
```

نوع اثر جوهر (مثلاً Galaxy، Gold، Silver) را که سبک بصری خط جوهر را تعریف می‌کند، دریافت می‌کند. مقدار از خصوصیت قلم‌مو "inkEffects" تجزیه می‌شود. اگر هیچ اثر شناخته‌شده‌ای مشخص نشده باشد، [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) بازگردانده می‌شود.

**بازگرداندن:**
int