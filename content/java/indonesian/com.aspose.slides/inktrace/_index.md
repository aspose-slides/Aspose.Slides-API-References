---
title: InkTrace
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili objek Trace.
type: docs
url: /id/com.aspose.slides/inktrace/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)
```
public class InkTrace implements IInkTrace
```

Mewakili objek Trace. Elemen Trace digunakan untuk merekam data yang ditangkap oleh digitizer. Ini berisi urutan titik yang dikodekan sesuai dengan spesifikasi yang diberikan oleh objek InkTraceFormat.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBrush()](#getBrush--) | Mendapatkan Brush untuk IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Hanya baca. |
| [getPoints()](#getPoints--) | Mendapatkan poin untuk IInkLine java.awt.geom.Point2D.Float Hanya baca. |
### getBrush() {#getBrush--}
```
public final IInkBrush getBrush()
```


Mendapatkan Brush untuk IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Hanya baca.

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
public final Point2D.Float[] getPoints()
```


Mendapatkan poin untuk IInkLine java.awt.geom.Point2D.Float Hanya baca.

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