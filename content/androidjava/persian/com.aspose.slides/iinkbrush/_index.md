---
title: IInkBrush
second_title: Aspose.Slides for Android via Java API Reference
description: نماینده‌ی قلم ردیابی.
type: docs
url: /fa/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

نماینده‌ی قلم ردیابی.
## متدها

| متد | توضیح |
| --- | --- |
| [getColor()](#getColor--) | رنگ براش را برای یک خط دریافت یا تنظیم می‌کند. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | رنگ براش را برای یک خط دریافت یا تنظیم می‌کند. |
| [getSize()](#getSize--) | اندازه براش را برای یک خط به پوینت‌ها دریافت یا تنظیم می‌کند. |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | اندازه براش را برای یک خط به پوینت‌ها دریافت یا تنظیم می‌کند. |
| [getInkEffect()](#getInkEffect--) | نوع اثر جوهر (مثلاً Galaxy، Gold، Silver) را دریافت می‌کند که سبک بصری خط جوهر را تعریف می‌کند. |
### getColor() {#getColor--}
```
public abstract Integer getColor()
```


رنگ براش را برای یک خط دریافت یا تنظیم می‌کند.

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
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```


رنگ براش را برای یک خط دریافت یا تنظیم می‌کند.

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
public abstract SizeF getSize()
```


اندازه براش را برای یک خط به پوینت‌ها دریافت یا تنظیم می‌کند.

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

**بازگشت:**
[SizeF](../../com.aspose.slides.android/sizef)
### setSize(SizeF value) {#setSize-com.aspose.slides.android.SizeF-}
```
public abstract void setSize(SizeF value)
```


اندازه براش را برای یک خط به پوینت‌ها دریافت یا تنظیم می‌کند.

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
public abstract int getInkEffect()
```


نوع اثر جوهر را دریافت می‌کند (مثلاً Galaxy، Gold، Silver) که سبک بصری خط جوهر را تعریف می‌کند. مقدار از ویژگی براش "inkEffects" تجزیه می‌شود. اگر هیچ اثر شناخته‌شده‌ای مشخص نشده باشد، [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) برگردانده می‌شود.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      Ink ink = (Ink) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkBrush brush = ink.getTraces()[0].getBrush();
>      System.out.println("InkEffects = " + brush.getInkEffect());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگشت:**
int