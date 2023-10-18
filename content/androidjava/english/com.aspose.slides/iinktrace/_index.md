---
title: IInkTrace
second_title: Aspose.Slides for Android via Java API Reference
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
| [getPoints()](#getPoints--) | Gets points for the IInkLine android.graphics.PointF Read-only. |
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
public abstract PointF[] getPoints()
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
