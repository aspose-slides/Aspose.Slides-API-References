---
title: IInkTrace
second_title: Aspose.Slides for Android via Java API Reference
description: Represents handwritten line in an Ink object.
type: docs
url: /es/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

Representa una línea manuscrita en un objeto Ink.
## Métodos

| Método | Descripción |
| --- | --- |
| [getBrush()](#getBrush--) | Obtiene Brush para el IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Solo lectura. |
| [getPoints()](#getPoints--) | Obtiene puntos para el IInkLine android.graphics.PointF Solo lectura. |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
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
public abstract PointF[] getPoints()
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