---
title: InkTrace
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een Trace-object voor.
type: docs
url: /nl/com.aspose.slides/inktrace/
---
**Erfelijkheid:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)
```
public class InkTrace implements IInkTrace
```

Stelt een Trace-object voor. Een Trace-element wordt gebruikt om de door de digitalisator vastgelegde gegevens vast te leggen. Het bevat een reeks punten gecodeerd volgens de specificatie die wordt gegeven door het InkTraceFormat-object.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getBrush()](#getBrush--) | Haalt Brush op voor de IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Alleen-lezen. |
| [getPoints()](#getPoints--) | Haalt punten op voor de IInkLine android.graphics.PointF Alleen-lezen. |
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

**Retourneert:**
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public final PointF[] getPoints()
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