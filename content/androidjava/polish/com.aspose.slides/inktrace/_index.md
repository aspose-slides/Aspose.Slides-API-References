---
title: InkTrace
second_title: Aspose.Slides dla Androida przy użyciu Java API Reference
description: Reprezentuje obiekt Trace.
type: docs
url: /pl/com.aspose.slides/inktrace/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)
```
public class InkTrace implements IInkTrace
```

Reprezentuje obiekt Trace. Element Trace jest używany do rejestrowania danych przechwyconych przez digitalizator. Zawiera sekwencję punktów zakodowaną zgodnie ze specyfikacją podaną przez obiekt InkTraceFormat.
## Metody

| Metoda | Opis |
| --- | --- |
| [getBrush()](#getBrush--) | Pobiera Brush dla IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Tylko do odczytu. |
| [getPoints()](#getPoints--) | Pobiera punkty dla IInkLine android.graphics.PointF Tylko do odczytu. |
### getBrush() {#getBrush--}
```
public final IInkBrush getBrush()
```


Pobiera Brush dla IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Tylko do odczytu.

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


**Zwraca:**
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public final PointF[] getPoints()
```


Pobiera punkty dla IInkLine android.graphics.PointF Tylko do odczytu.

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

**Zwraca:**
android.graphics.PointF[]