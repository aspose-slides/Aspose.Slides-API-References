---
title: IInkTrace
second_title: Aspose.Slides for Java API Reference
description: Representa uma linha manuscrita em um objeto Ink.
type: docs
url: /pt/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

Representa uma linha manuscrita em um objeto Ink.
## Métodos

| Método | Descrição |
| --- | --- |
| [getBrush()](#getBrush--) | Obtém Brush para o IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Somente leitura. |
| [getPoints()](#getPoints--) | Obtém pontos para o IInkLine java.awt.geom.Point2D.Float Somente leitura. |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
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
public abstract Point2D.Float[] getPoints()
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