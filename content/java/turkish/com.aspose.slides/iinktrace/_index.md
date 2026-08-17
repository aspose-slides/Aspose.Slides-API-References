---
title: IInkTrace
second_title: Aspose.Slides for Java API Reference
description: Represents handwritten line in an Ink object.
type: docs
url: /tr/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

Bir Ink nesnesindeki el yazısı çizgiyi temsil eder.

## Yöntemler

| Method | Açıklama |
| --- | --- |
| [getBrush()](#getBrush--) | IInkLine için Brush'ı al [IInkBrush](../../com.aspose.slides/iinkbrush) Yalnızca okunur. |
| [getPoints()](#getPoints--) | IInkLine için java.awt.geom.Point2D.Float noktaları al Yalnızca okunur. |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```


IInkLine için Brush'ı al [IInkBrush](../../com.aspose.slides/iinkbrush) Yalnızca okunur.

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


**Döndürür:**
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public abstract Point2D.Float[] getPoints()
```


IInkLine için java.awt.geom.Point2D.Float noktaları al Yalnızca okunur.

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

**Döndürür:**
java.awt.geom.Point2D.Float[]