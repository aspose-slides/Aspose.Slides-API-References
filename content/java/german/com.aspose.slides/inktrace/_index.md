---
title: InkTrace
second_title: Aspose.Slides für Java API Referenz
description: Stellt ein Trace-Objekt dar.
type: docs
url: /de/com.aspose.slides/inktrace/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)
```
public class InkTrace implements IInkTrace
```

Stellt ein Trace-Objekt dar. Ein Trace-Element wird verwendet, um die vom Digitalisierer erfassten Daten aufzuzeichnen. Es enthält eine Sequenz von Punkten, die gemäß der vom InkTraceFormat-Objekt angegebenen Spezifikation codiert sind.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBrush()](#getBrush--) | Ermittelt Brush für die IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Nur-Lesen. |
| [getPoints()](#getPoints--) | Ermittelt Punkte für die IInkLine java.awt.geom.Point2D.Float Nur-Lesen. |
### getBrush() {#getBrush--}
```
public final IInkBrush getBrush()
```


Ermittelt Brush für die IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Nur-Lesen.

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
public final Point2D.Float[] getPoints()
```


Ermittelt Punkte für die IInkLine java.awt.geom.Point2D.Float Nur-Lesen.

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