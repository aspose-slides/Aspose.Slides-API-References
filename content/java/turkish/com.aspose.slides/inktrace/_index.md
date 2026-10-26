---
title: InkTrace
second_title: Aspose.Slides için Java API Referansı
description: Bir Trace nesnesini temsil eder.
type: docs
url: /tr/com.aspose.slides/inktrace/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)
```
public class InkTrace implements IInkTrace
```

Bir Trace nesnesini temsil eder. Bir Trace öğesi, dijitizer tarafından yakalanan verileri kaydetmek için kullanılır. InkTraceFormat nesnesi tarafından verilen spesifikasyona göre kodlanmış bir dizi nokta içerir.

## Metotlar

| Method | Açıklama |
| --- | --- |
| [getBrush()](#getBrush--) | IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) için Brush alır Sadece okuma. |
| [getPoints()](#getPoints--) | IInkLine java.awt.geom.Point2D.Float için noktaları alır Sadece okuma. |
### getBrush() {#getBrush--}
```
public final IInkBrush getBrush()
```


IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) için Brush alır Sadece okuma.

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
public final Point2D.Float[] getPoints()
```


IInkLine java.awt.geom.Point2D.Float için noktaları alır Sadece okuma.

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