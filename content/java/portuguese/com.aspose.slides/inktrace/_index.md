---
title: InkTrace
second_title: Referência da API Aspose.Slides para Java
description: Representa um objeto Trace.
type: docs
url: /pt/com.aspose.slides/inktrace/
---
**Herança:**
java.lang.Object

**Todas as interfaces implementadas:**
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)
```
public class InkTrace implements IInkTrace
```

Representa um objeto Trace. Um elemento Trace é usado para registrar os dados capturados pelo digitizador. Ele contém uma sequência de pontos codificados de acordo com a especificação fornecida pelo objeto InkTraceFormat.
## Métodos

| Método | Descrição |
| --- | --- |
| [getBrush()](#getBrush--) | Obtém Brush para o IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Somente leitura. |
| [getPoints()](#getPoints--) | Obtém pontos para o IInkLine java.awt.geom.Point2D.Float Somente leitura. |
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
public final Point2D.Float[] getPoints()
```

Obtém pontos para o IInkLine java.awt.geom.Point2D.Float Somente leitura.

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

**Retorna:**
java.awt.geom.Point2D.Float[]