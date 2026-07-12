---
title: IInkTrace
second_title: Aspose.Slides for Android via Java API Reference
description: Representa linha manuscrita em um objeto Ink.
type: docs
url: /pt/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

Representa linha manuscrita em um objeto Ink.
## Métodos

| Method | Description |
| --- | --- |
| [getBrush()](#getBrush--) | Obtém Brush para o IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Somente leitura. |
| [getPoints()](#getPoints--) | Obtém pontos para o IInkLine android.graphics.PointF Somente leitura. |
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
public abstract PointF[] getPoints()
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