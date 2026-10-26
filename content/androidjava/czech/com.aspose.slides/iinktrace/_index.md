---
title: IInkTrace
second_title: Aspose.Slides for Android via Java API Reference
description: Represents handwritten line in an Ink object.
type: docs
url: /cs/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

Představuje ručně psanou čáru v objektu Ink.
## Metody

| Metoda | Popis |
| --- | --- |
| [getBrush()](#getBrush--) | Získá Brush pro IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Pouze pro čtení. |
| [getPoints()](#getPoints--) | Získá body pro IInkLine android.graphics.PointF Pouze pro čtení. |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```


Získá Brush pro IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Pouze pro čtení.

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

**Vrací:**
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public abstract PointF[] getPoints()
```


Získá body pro IInkLine android.graphics.PointF Pouze pro čtení.

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

**Vrací:**
android.graphics.PointF[]