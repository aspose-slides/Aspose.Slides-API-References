---
title: IInkTrace
second_title: Aspose.Slides for Java API Reference
description: Represents handwritten line in an Ink object.
type: docs
url: /id/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

Mewakili garis tulisan tangan dalam objek Ink.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBrush()](#getBrush--) | Mendapatkan Brush untuk IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Hanya-baca. |
| [getPoints()](#getPoints--) | Mendapatkan titik untuk IInkLine java.awt.geom.Point2D.Float Hanya-baca. |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```


Mendapatkan Brush untuk IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Hanya-baca.

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


**Mengembalikan:**
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public abstract Point2D.Float[] getPoints()
```


Mendapatkan titik untuk IInkLine java.awt.geom.Point2D.Float Hanya-baca.

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

**Mengembalikan:**
java.awt.geom.Point2D.Float[]