---
title: InkTrace
second_title: Aspose.Slides for Java API hivatkozás
description: Egy Trace objektumot reprezentál.
type: docs
url: /hu/com.aspose.slides/inktrace/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)
```
public class InkTrace implements IInkTrace
```

Egy Trace objektumot reprezentál. A Trace elem a digitalizáló által rögzített adatok felvételére szolgál. Pontsorozatot tartalmaz, amely az InkTraceFormat objektum által megadott specifikáció szerint van kódolva.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getBrush()](#getBrush--) | Lekéri a Brush-t az IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) számára csak olvasható. |
| [getPoints()](#getPoints--) | Lekéri a pontokat az IInkLine java.awt.geom.Point2D.Float számára csak olvasható. |
### getBrush() {#getBrush--}
```
public final IInkBrush getBrush()
```


Lekéri a Brush-t az IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) számára csak olvasható.

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
public final Point2D.Float[] getPoints()
```


Lekéri a pontokat az IInkLine java.awt.geom.Point2D.Float számára csak olvasható.

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