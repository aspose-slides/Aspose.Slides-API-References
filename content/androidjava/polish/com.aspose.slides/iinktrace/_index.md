---
title: IInkTrace
second_title: Aspose.Slides for Android via Java API Reference
description: Represents handwritten line in an Ink object.
type: docs
url: /pl/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

Reprezentuje odręczną linię w obiekcie Ink.
## Metody

| Metoda | Opis |
| --- | --- |
| [getBrush()](#getBrush--) | Pobiera Brush dla IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Tylko do odczytu. |
| [getPoints()](#getPoints--) | Pobiera punkty dla IInkLine android.graphics.PointF Tylko do odczytu. |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```


Pobiera Brush dla IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Tylko do odczytu.

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

**Zwraca:**
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public abstract PointF[] getPoints()
```


Pobiera punkty dla IInkLine android.graphics.PointF Tylko do odczytu.

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

**Zwraca:**
android.graphics.PointF[]