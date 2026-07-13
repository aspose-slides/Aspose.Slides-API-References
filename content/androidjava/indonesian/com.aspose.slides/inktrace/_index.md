---
title: InkTrace
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili objek Trace.
type: docs
url: /id/com.aspose.slides/inktrace/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)
```
public class InkTrace implements IInkTrace
```

Mewakili objek Trace. Sebuah elemen Trace digunakan untuk merekam data yang ditangkap oleh digitizer. Ini berisi urutan titik yang dikodekan sesuai spesifikasi yang diberikan oleh objek InkTraceFormat.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBrush()](#getBrush--) | Mendapatkan Brush untuk IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Hanya-baca. |
| [getPoints()](#getPoints--) | Mendapatkan titik untuk IInkLine android.graphics.PointF Hanya-baca. |
### getBrush() {#getBrush--}
```
public final IInkBrush getBrush()
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
public final PointF[] getPoints()
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