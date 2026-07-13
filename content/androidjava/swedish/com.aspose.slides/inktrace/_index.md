---
title: InkTrace
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar ett Trace-objekt.
type: docs
url: /sv/com.aspose.slides/inktrace/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)
```
public class InkTrace implements IInkTrace
```

Representerar ett Trace-objekt. Ett Trace-element används för att registrera data som fångas av digitizern. Det innehåller en sekvens av punkter som kodas enligt specifikationen som ges av InkTraceFormat-objektet.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBrush()](#getBrush--) | Hämtar Brush för IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) skrivskyddad. |
| [getPoints()](#getPoints--) | Hämtar punkter för IInkLine android.graphics.PointF skrivskyddad. |
### getBrush() {#getBrush--}
```
public final IInkBrush getBrush()
```


Hämtar Brush för IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) skrivskyddad.

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
public final PointF[] getPoints()
```


Hämtar punkter för IInkLine android.graphics.PointF skrivskyddad.

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

**Returnerar:**
android.graphics.PointF[]