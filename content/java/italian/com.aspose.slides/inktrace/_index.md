---
title: InkTrace
second_title: Riferimento API Aspose.Slides per Java
description: Rappresenta un oggetto Trace.
type: docs
url: /it/com.aspose.slides/inktrace/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)
```
public class InkTrace implements IInkTrace
```

Rappresenta un oggetto Trace. Un elemento Trace è usato per registrare i dati acquisiti dal digitalizzatore. Contiene una sequenza di punti codificati secondo la specifica fornita dall'oggetto InkTraceFormat.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBrush()](#getBrush--) | Ottiene Brush per l'IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Sola lettura. |
| [getPoints()](#getPoints--) | Ottiene i punti per l'IInkLine java.awt.geom.Point2D.Float Sola lettura. |
### getBrush() {#getBrush--}
```
public final IInkBrush getBrush()
```


Ottiene Brush per l'IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Sola lettura.

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

**Restituisce:**
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public final Point2D.Float[] getPoints()
```


Ottiene i punti per l'IInkLine java.awt.geom.Point2D.Float Sola lettura.

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

**Restituisce:**
java.awt.geom.Point2D.Float[]