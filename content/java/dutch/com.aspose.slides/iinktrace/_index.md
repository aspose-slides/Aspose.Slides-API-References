---
title: IInkTrace
second_title: Aspose.Slides for Java API Reference
description: Stelt een handgeschreven lijn in een Ink-object voor.
type: docs
url: /nl/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

Stelt een handgeschreven lijn in een Ink-object voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getBrush()](#getBrush--) | Haalt Brush voor de IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) alleen-lezen. |
| [getPoints()](#getPoints--) | Haalt punten voor de IInkLine java.awt.geom.Point2D.Float alleen-lezen. |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```


Haalt Brush voor de IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) alleen-lezen.

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
public abstract Point2D.Float[] getPoints()
```


Haalt punten voor de IInkLine java.awt.geom.Point2D.Float alleen-lezen.

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

**Retourneert:**
java.awt.geom.Point2D.Float[]