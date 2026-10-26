---
title: InkTrace
second_title: Aspose.Slides für Android über Java API-Referenz
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

Stellt ein Trace-Objekt dar. Ein Trace-Element wird verwendet, um die vom Digitizer erfassten Daten aufzuzeichnen. Es enthält eine Sequenz von Punkten, die gemäß der Spezifikation des InkTraceFormat-Objekts kodiert sind.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBrush()](#getBrush--) | Liefert Brush für die IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Nur-lesen. |
| [getPoints()](#getPoints--) | Liefert Punkte für die IInkLine android.graphics.PointF Nur-lesen. |
### getBrush() {#getBrush--}
```
public final IInkBrush getBrush()
```


Liefert Brush für die IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Nur-lesen.

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
public final PointF[] getPoints()
```


Liefert Punkte für die IInkLine android.graphics.PointF Nur-lesen.

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