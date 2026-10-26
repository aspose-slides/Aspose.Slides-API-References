---
title: IInkBrush
second_title: Aspose.Slides for Java API Reference
description: Represents trace brush.
type: docs
url: /fa/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

نمایانگر قلم‌دست.

## متدها

| Method | Description |
| --- | --- |
| [getColor()](#getColor--) | رنگ قلم‌دست برای یک خط را دریافت یا تنظیم می‌کند. |
| [setColor(Color value)](#setColor-java.awt.Color-) | رنگ قلم‌دست برای یک خط را دریافت یا تنظیم می‌کند. |
| [getSize()](#getSize--) | اندازه قلم‌دست برای یک خط بر حسب نقطه را دریافت یا تنظیم می‌کند. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | اندازه قلم‌دست برای یک خط بر حسب نقطه را دریافت یا تنظیم می‌کند. |
| [getInkEffect()](#getInkEffect--) | نوع اثر جوهر (مانند Galaxy، Gold، Silver) که سبک بصری قلم‌دست را تعریف می‌کند. |

### getColor() {#getColor--}
```
public abstract Color getColor()
```

رنگ قلم‌دست برای یک خط را دریافت یا تنظیم می‌کند.

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
public abstract void setColor(Color value)
```

رنگ قلم‌دست برای یک خط را دریافت یا تنظیم می‌کند.

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
public abstract Dimension2D getSize()
```

اندازه قلم‌دست برای یک خط بر حسب نقطه را دریافت یا تنظیم می‌کند.

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

**بازگشت:**  
java.awt.geom.Dimension2D

### setSize(Dimension2D value) {#setSize-java.awt.geom.Dimension2D-}
```
public abstract void setSize(Dimension2D value)
```

اندازه قلم‌دست برای یک خط بر حسب نقطه را دریافت یا تنظیم می‌کند.

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
public abstract int getInkEffect()
```

نوع اثر جوهر (مانند Galaxy، Gold، Silver) که سبک بصری قلم‌دست را تعریف می‌کند. مقدار از ویژگی brush "inkEffects" تجزیه می‌شود. اگر هیچ اثر شناخته‌شده‌ای مشخص نشود، [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) برگردانده می‌شود.

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