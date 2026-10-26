---
title: IInkTrace
second_title: Aspose.Slides untuk Android via Java API Reference
description: Mewakili garis tulisan tangan dalam objek Ink.
type: docs
url: /id/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

Mewakili garis tulisan tangan dalam objek Ink.
## Metode

| Method | Description |
| --- | --- |
| [getBrush()](#getBrush--) | Mendapatkan Brush untuk IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Hanya-baca. |
| [getPoints()](#getPoints--) | Mendapatkan titik untuk IInkLine android.graphics.PointF Hanya-baca. |
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
public abstract PointF[] getPoints()
```


Mendapatkan titik untuk IInkLine android.graphics.PointF Hanya-baca.

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

**Mengembalikan:**
android.graphics.PointF[]