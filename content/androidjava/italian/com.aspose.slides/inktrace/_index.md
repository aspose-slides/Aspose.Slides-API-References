---
title: InkTrace
second_title: Aspose.Slides for Android via Java API Reference
description: Rappresenta un oggetto Trace.
type: docs
url: /it/com.aspose.slides/inktrace/
---
**Eredità:**
java.lang.Object

**Tutte le Interfacce Implementate:**
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)
```
public class InkTrace implements IInkTrace
```

Rappresenta un oggetto Trace. Un elemento Trace è usato per registrare i dati catturati dal digitalizzatore. Contiene una sequenza di punti codificati secondo le specifiche fornite dall'oggetto InkTraceFormat.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBrush()](#getBrush--) | Ottiene Brush per il IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Sola lettura. |
| [getPoints()](#getPoints--) | Ottiene punti per il IInkLine android.graphics.PointF Sola lettura. |

### getBrush() {#getBrush--}
```
public final IInkBrush getBrush()
```

Ottiene Brush per il IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Sola lettura.

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
public final PointF[] getPoints()
```

Ottiene punti per il IInkLine android.graphics.PointF Sola lettura.

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

**Restituisce:**
android.graphics.PointF[]