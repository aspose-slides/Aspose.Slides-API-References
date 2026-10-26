---
title: IInkTrace
second_title: Aspose.Slides for Android via Java API Reference
description: Stelt een handgeschreven lijn voor in een Ink-object.
type: docs
url: /nl/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

Stelt een handgeschreven lijn voor in een Ink-object.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getBrush()](#getBrush--) | Haalt Brush op voor de IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Alleen-lezen. |
| [getPoints()](#getPoints--) | Haalt punten op voor de IInkLine android.graphics.PointF Alleen-lezen. |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```


Haalt Brush op voor de IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Alleen-lezen.

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

**Retourneert:**
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public abstract PointF[] getPoints()
```


Haalt punten op voor de IInkLine android.graphics.PointF Alleen-lezen.

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

**Retourneert:**
android.graphics.PointF[]