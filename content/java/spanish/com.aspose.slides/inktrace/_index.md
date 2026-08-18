---
title: InkTrace
second_title: Referencia de API de Aspose.Slides para Java
description: Representa un objeto Trace.
type: docs
url: /es/com.aspose.slides/inktrace/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)
```
public class InkTrace implements IInkTrace
```

Representa un objeto Trace. Un elemento Trace se usa para registrar los datos capturados por el digitalizador. Contiene una secuencia de puntos codificados según la especificación dada por el objeto InkTraceFormat.

## Métodos

| Método | Descripción |
| --- | --- |
| [getBrush()](#getBrush--) | Obtiene Brush para el IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Solo lectura. |
| [getPoints()](#getPoints--) | Obtiene puntos para el IInkLine java.awt.geom.Point2D.Float Solo lectura. |
### getBrush() {#getBrush--}
```
public final IInkBrush getBrush()
```


Obtiene Brush para el IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Solo lectura.

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

**Devuelve:**
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public final Point2D.Float[] getPoints()
```


Obtiene puntos para el IInkLine java.awt.geom.Point2D.Float Solo lectura.

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

**Devuelve:**
java.awt.geom.Point2D.Float[]