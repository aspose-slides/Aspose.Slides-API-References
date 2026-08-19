---
title: InkTrace
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een Trace-object voor.
type: docs
url: /nl/com.aspose.slides/inktrace/
---
**Overerving:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)
```
public class InkTrace implements IInkTrace
```

Stelt een Trace-object voor. Een Trace-element wordt gebruikt om de door de digitizer vastgelegde gegevens op te nemen. Het bevat een reeks punten gecodeerd volgens de specificatie die wordt gegeven door het InkTraceFormat-object.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getBrush()](#getBrush--) | Haalt Brush op voor de IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Alleen-lezen. |
| [getPoints()](#getPoints--) | Haalt punten op voor de IInkLine java.awt.geom.Point2D.Float Alleen-lezen. |
### getBrush() {#getBrush--}
```
public final IInkBrush getBrush()
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

**Retourwaarde:**
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public final Point2D.Float[] getPoints()
```

Haalt punten op voor de IInkLine java.awt.geom.Point2D.Float Alleen-lezen.

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

**Retourwaarde:**
java.awt.geom.Point2D.Float[]