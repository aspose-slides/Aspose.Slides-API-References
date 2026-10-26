---
title: InkTrace
second_title: Aspose.Slides para Android vía Referencia de API Java
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

Representa un objeto Trace. Un elemento Trace se utiliza para registrar los datos capturados por el digitalizador. Contiene una secuencia de puntos codificados según la especificación dada por el objeto InkTraceFormat.

## Métodos

| Método | Descripción |
| --- | --- |
| [getBrush()](#getBrush--) | Obtiene Brush para el IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Solo lectura. |
| [getPoints()](#getPoints--) | Obtiene puntos para el IInkLine android.graphics.PointF Solo lectura. |
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
public final PointF[] getPoints()
```


Obtiene puntos para el IInkLine android.graphics.PointF Solo lectura.

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

**Devuelve:**
android.graphics.PointF[]