---
title: InkTrace
second_title: Aspose.Slides Androidra a Java API referencián keresztül
description: Egy Trace objektumot reprezentál.
type: docs
url: /hu/com.aspose.slides/inktrace/
---
**Öröklés:**
java.lang.Object

**Minden implementált interfész:**
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)
```
public class InkTrace implements IInkTrace
```

Egy Trace objektumot reprezentál. Egy Trace elemet a digitizer által rögzített adatok felvételére használnak. Ez egy pontszekvenciát tartalmaz, amelyet az InkTraceFormat objektum által megadott specifikáció szerint kódolnak.

## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getBrush()](#getBrush--) | A Brush-t adja a IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) számára, csak olvasható. |
| [getPoints()](#getPoints--) | A pontokat adja a IInkLine android.graphics.PointF számára, csak olvasható. |

### getBrush() {#getBrush--}
```
public final IInkBrush getBrush()
```

A Brush-t adja a IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) számára, csak olvasható.

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
public final PointF[] getPoints()
```

A pontokat adja a IInkLine android.graphics.PointF számára, csak olvasható.

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