---
title: IInkTrace
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar handskriven linje i ett Ink-objekt.
type: docs
url: /sv/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

Representerar handskriven linje i ett Ink-objekt.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBrush()](#getBrush--) | Hämtar Brush för IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) skrivskyddad. |
| [getPoints()](#getPoints--) | Hämtar punkter för IInkLine android.graphics.PointF skrivskyddad. |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```


Hämtar Brush för IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) skrivskyddad.

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

**Returnerar:**
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public abstract PointF[] getPoints()
```


Hämtar punkter för IInkLine android.graphics.PointF skrivskyddad.

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

**Returnerar:**
android.graphics.PointF[]