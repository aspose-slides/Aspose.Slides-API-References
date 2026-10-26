---
title: IInkTrace
second_title: Aspose.Slides per Android tramite Java API Reference
description: Rappresenta una linea scritta a mano in un oggetto Ink.
type: docs
url: /it/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

Rappresenta una linea scritta a mano in un oggetto Ink.
## Methods

| Metodo | Descrizione |
| --- | --- |
| [getBrush()](#getBrush--) | Ottiene Brush per IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Sola lettura. |
| [getPoints()](#getPoints--) | Ottiene punti per IInkLine android.graphics.PointF Sola lettura. |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```


Ottiene Brush per IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Sola lettura.

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
public abstract PointF[] getPoints()
```


Ottiene punti per IInkLine android.graphics.PointF Sola lettura.

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