---
title: IInkTrace
second_title: Aspose.Slides for Java API Reference
description: Representerar handskriven linje i ett Ink-objekt.
type: docs
url: /sv/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

Representerar handskriven linje i ett Ink-objekt.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBrush()](#getBrush--) | Hämtar Brush för IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Endast läsning. |
| [getPoints()](#getPoints--) | Hämtar punkter för IInkLine java.awt.geom.Point2D.Float Endast läsning. |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```

Hämtar Brush för IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Endast läsning.

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

**Returnerar:**
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public abstract Point2D.Float[] getPoints()
```

Hämtar punkter för IInkLine java.awt.geom.Point2D.Float Endast läsning.

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

**Returnerar:**
java.awt.geom.Point2D.Float[]