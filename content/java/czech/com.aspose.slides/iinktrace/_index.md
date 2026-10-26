---
title: IInkTrace
second_title: Aspose.Slides for Java API Reference
description: Reprezentuje ručně psanou čáru v objektu Ink.
type: docs
url: /cs/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

Reprezentuje ručně psanou čáru v objektu Ink.
## Metody

| Metoda | Popis |
| --- | --- |
| [getBrush()](#getBrush--) | Načte Brush pro IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Pouze pro čtení. |
| [getPoints()](#getPoints--) | Načte body pro IInkLine java.awt.geom.Point2D.Float Pouze pro čtení. |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```


Načte Brush pro IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Pouze pro čtení.

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

**Vrací:**
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public abstract Point2D.Float[] getPoints()
```


Načte body pro IInkLine java.awt.geom.Point2D.Float Pouze pro čtení.

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

**Vrací:**
java.awt.geom.Point2D.Float[]