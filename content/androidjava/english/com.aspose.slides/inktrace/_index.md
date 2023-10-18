---
title: InkTrace
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an Trace object.
type: docs
url: /com.aspose.slides/inktrace/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)
```
public class InkTrace implements IInkTrace
```

Represents an Trace object. A Trace element is used to record the data captured by the digitizer. It contains a sequence of points encoded according to the specification given by the InkTraceFormat object.
## Methods

| Method | Description |
| --- | --- |
| [getBrush()](#getBrush--) | Gets Brush for the IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Read-only. |
| [getPoints()](#getPoints--) | Gets points for the IInkLine android.graphics.PointF Read-only. |
### getBrush() {#getBrush--}
```
public final IInkBrush getBrush()
```


Gets Brush for the IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Read-only.

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

**Returns:**
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public final PointF[] getPoints()
```


Gets points for the IInkLine android.graphics.PointF Read-only.

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

**Returns:**
android.graphics.PointF[]
