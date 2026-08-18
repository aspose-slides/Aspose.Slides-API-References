---
title: IInkTrace
second_title: Aspose.Slides para Java Referencia de API
description: Representa una línea escrita a mano en un objeto Ink.
type: docs
url: /es/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

Representa una línea escrita a mano en un objeto Ink.
## Métodos

| Method | Description |
| --- | --- |
| [getBrush()](#getBrush--) | Obtiene Brush para la IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Solo lectura. |
| [getPoints()](#getPoints--) | Obtiene points para la IInkLine java.awt.geom.Point2D.Float Solo lectura. |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```


Obtiene Brush para la IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Solo lectura.

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
public abstract Point2D.Float[] getPoints()
```


Obtiene points para la IInkLine java.awt.geom.Point2D.Float Solo lectura.

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