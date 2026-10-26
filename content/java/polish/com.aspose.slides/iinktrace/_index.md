---
title: IInkTrace
second_title: Aspose.Slides for Java API Reference
description: Reprezentuje odręczną linię w obiekcie Ink.
type: docs
url: /pl/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

Reprezentuje odręczną linię w obiekcie Ink.
## Metody

| Metoda | Opis |
| --- | --- |
| [getBrush()](#getBrush--) | Pobiera Brush dla IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Tylko do odczytu. |
| [getPoints()](#getPoints--) | Pobiera punkty dla IInkLine java.awt.geom.Point2D.Float Tylko do odczytu. |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```


Pobiera Brush dla IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Tylko do odczytu.

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

**Zwraca:**
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public abstract Point2D.Float[] getPoints()
```


Pobiera punkty dla IInkLine java.awt.geom.Point2D.Float Tylko do odczytu.

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

**Zwraca:**
java.awt.geom.Point2D.Float[]