---
title: IInkTrace
second_title: Aspose.Slides for Java API Reference
description: Represents handwritten line in an Ink object.
type: docs
url: /com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

Represents handwritten line in an Ink object.
## Methods

| Method | Description |
| --- | --- |
| [getBrush()](#getBrush--) | Gets Brush for the IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Read-only. |
| [getPoints()](#getPoints--) | Gets points for the IInkLine java.awt.geom.Point2D.Float Read-only. |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
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
public abstract Point2D.Float[] getPoints()
```


Gets points for the IInkLine java.awt.geom.Point2D.Float Read-only.

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

**Returns:**
java.awt.geom.Point2D.Float[]
