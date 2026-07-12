---
title: InkTrace
second_title: Aspose.Slides para Android via Referência de API Java
description: Representa um objeto Trace.
type: docs
url: /pt/com.aspose.slides/inktrace/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)
```
public class InkTrace implements IInkTrace
```

Representa um objeto Trace. Um elemento Trace é usado para registrar os dados capturados pelo digitalizador. Ele contém uma sequência de pontos codificados de acordo com a especificação fornecida pelo objeto InkTraceFormat.

## Métodos

| Método | Descrição |
| --- | --- |
| [getBrush()](#getBrush--) | Obtém Brush para o IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Somente leitura. |
| [getPoints()](#getPoints--) | Obtém pontos para o IInkLine android.graphics.PointF Somente leitura. |

### getBrush() {#getBrush--}
```
public final IInkBrush getBrush()
```

Obtém Brush para o IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Somente leitura.

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


**Retorna:**
[IInkBrush](../../com.aspose.slides/iinkbrush)

### getPoints() {#getPoints--}
```
public final PointF[] getPoints()
```

Obtém pontos para o IInkLine android.graphics.PointF Somente leitura.

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

**Retorna:**
android.graphics.PointF[]