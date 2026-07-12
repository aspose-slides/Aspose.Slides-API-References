---
title: IInkTrace
second_title: Aspose.Slides for Android Java API referenciája
description: Kézzel írt vonalat képvisel egy Ink objektumban.
type: docs
url: /hu/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

Kézzel írt vonalat képvisel egy Ink objektumban.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getBrush()](#getBrush--) | Eléri a Brush-t az IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) számára csak olvasható módon. |
| [getPoints()](#getPoints--) | Eléri a pontokat az IInkLine android.graphics.PointF számára csak olvasható módon. |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```


Eléri a Brush-t az IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) számára csak olvasható módon.

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

**Visszatér:** 
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public abstract PointF[] getPoints()
```


Eléri a pontokat az IInkLine android.graphics.PointF számára csak olvasható módon.

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

**Visszatér:** 
android.graphics.PointF[]