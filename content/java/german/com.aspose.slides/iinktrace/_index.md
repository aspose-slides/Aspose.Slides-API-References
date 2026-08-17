---
title: IInkTrace
second_title: Aspose.Slides for Java API Reference
description: Represents handwritten line in an Ink object.
type: docs
url: /de/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

Stellt eine handschriftliche Linie in einem Ink-Objekt dar.
## Methoden

| Method | Description |
| --- | --- |
| [getBrush()](#getBrush--) | Gibt Brush für die IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Nur lesend. |
| [getPoints()](#getPoints--) | Gibt Punkte für die IInkLine java.awt.geom.Point2D.Float Nur lesend. |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```


Gibt Brush für die IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Nur lesend.

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

**Rückgabe:**
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public abstract Point2D.Float[] getPoints()
```


Gibt Punkte für die IInkLine java.awt.geom.Point2D.Float Nur lesend.

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

**Rückgabe:**
java.awt.geom.Point2D.Float[]