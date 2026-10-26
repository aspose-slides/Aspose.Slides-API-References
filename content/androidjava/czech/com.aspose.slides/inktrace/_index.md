---
title: InkTrace
second_title: Aspose.Slides pro Android přes Java API Reference
description: Representuje objekt Trace.
type: docs
url: /cs/com.aspose.slides/inktrace/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)
```
public class InkTrace implements IInkTrace
```

Representuje objekt Trace. Prvek Trace se používá k zaznamenání dat zachycených digitalizérem. Obsahuje sekvenci bodů zakódovaných podle specifikace poskytnuté objektem InkTraceFormat.
## Metody

| Method | Description |
| --- | --- |
| [getBrush()](#getBrush--) | Získá Brush pro IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Pouze pro čtení. |
| [getPoints()](#getPoints--) | Získá body pro IInkLine android.graphics.PointF Pouze pro čtení. |
### getBrush() {#getBrush--}
```
public final IInkBrush getBrush()
```


Získá Brush pro IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Pouze pro čtení.

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

**Vrací:**
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public final PointF[] getPoints()
```


Získá body pro IInkLine android.graphics.PointF Pouze pro čtení.

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

**Vrací:**
android.graphics.PointF[]