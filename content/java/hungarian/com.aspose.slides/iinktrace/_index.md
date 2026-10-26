---
title: IInkTrace
second_title: Aspose.Slides for Java API Reference
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
| [getBrush()](#getBrush--) | Lekéri a Brush-et az IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) számára, csak olvasható. |
| [getPoints()](#getPoints--) | Lekéri a pontokat az IInkLine java.awt.geom.Point2D.Float esetén, csak olvasható. |

### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```

Lekéri a Brush-et az IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) számára, csak olvasható.

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
public abstract Point2D.Float[] getPoints()
```

Lekéri a pontokat az IInkLine java.awt.geom.Point2D.Float esetén, csak olvasható.

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


**Visszatér:**
java.awt.geom.Point2D.Float[]