---
title: IInkTrace
second_title: Aspose.Slides for Android via Java API Reference
description: Bir Ink nesnesindeki el yazısı satırı temsil eder.
type: docs
url: /tr/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

Bir Ink nesnesindeki el yazısı satırı temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBrush()](#getBrush--) | IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) için Brush alır Yalnızca okuma. |
| [getPoints()](#getPoints--) | IInkLine android.graphics.PointF için noktaları alır Yalnızca okuma. |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```


IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) için Brush alır Yalnızca okuma.

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
public abstract PointF[] getPoints()
```


IInkLine android.graphics.PointF için noktaları alır Yalnızca okuma.

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