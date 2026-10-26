---
title: InkTrace
second_title: Aspose.Slides for Android üzerinden Java API Referansı
description: Bir Trace nesnesini temsil eder.
type: docs
url: /tr/com.aspose.slides/inktrace/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)
```
public class InkTrace implements IInkTrace
```

Bir Trace nesnesini temsil eder. Bir Trace öğesi, dijitalleştirici tarafından yakalanan verileri kaydetmek için kullanılır. InkTraceFormat nesnesi tarafından verilen özelliğe göre kodlanmış bir nokta dizisi içerir.

## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getBrush()](#getBrush--) | IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) için Brush'ı alır. Salt-okunur. |
| [getPoints()](#getPoints--) | IInkLine android.graphics.PointF için noktaları alır. Salt-okunur. |

### getBrush() {#getBrush--}
```
public final IInkBrush getBrush()
```

IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) için Brush'ı alır. Salt-okunur.

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
public final PointF[] getPoints()
```

IInkLine android.graphics.PointF için noktaları alır. Salt-okunur.

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


**Döndürür:**
android.graphics.PointF[]