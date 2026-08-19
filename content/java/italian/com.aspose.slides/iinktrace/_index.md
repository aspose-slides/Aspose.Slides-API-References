---
title: IInkTrace
second_title: Aspose.Slides per Java – Riferimento API
description: Rappresenta una linea scritta a mano in un oggetto Ink.
type: docs
url: /it/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

Rappresenta una linea scritta a mano in un oggetto Ink.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBrush()](#getBrush--) | Ottiene Brush per l'IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Read-only. |
| [getPoints()](#getPoints--) | Ottiene i punti per l'IInkLine java.awt.geom.Point2D.Float Read-only. |

### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```

Ottiene Brush per l'IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Read-only.

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
public abstract Point2D.Float[] getPoints()
```

Ottiene i punti per l'IInkLine java.awt.geom.Point2D.Float Read-only.

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