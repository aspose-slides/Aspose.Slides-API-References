---
title: IInkTrace
second_title: Aspose.Slides for Android via Java API Reference
description: Represents handwritten line in an Ink object.
type: docs
url: /de/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

Stellt eine handgeschriebene Linie in einem Ink-Objekt dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBrush()](#getBrush--) | Liefert Brush für die IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Nur lesbar. |
| [getPoints()](#getPoints--) | Liefert Punkte für die IInkLine android.graphics.PointF Nur lesbar. |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```


Liefert Brush für die IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Nur lesbar.

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

**Rückgabewert:**
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public abstract PointF[] getPoints()
```


Liefert Punkte für die IInkLine android.graphics.PointF Nur lesbar.

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

**Rückgabewert:**
android.graphics.PointF[]