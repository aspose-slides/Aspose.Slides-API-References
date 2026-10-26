---
title: IInkTrace
second_title: Aspose.Slides for Android via Java API Reference
description: Represents handwritten line in an Ink object.
type: docs
url: /th/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

แทนบรรทัดที่เขียนด้วยมือในวัตถุ Ink.

## เมธอด

| Method | Description |
| --- | --- |
| [getBrush()](#getBrush--) | รับ Brush สำหรับ IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) อ่านอย่างเดียว. |
| [getPoints()](#getPoints--) | รับจุดสำหรับ IInkLine android.graphics.PointF อ่านอย่างเดียว. |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```

รับ Brush สำหรับ IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) อ่านอย่างเดียว.

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

**คืนค่า:**
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public abstract PointF[] getPoints()
```

รับจุดสำหรับ IInkLine android.graphics.PointF อ่านอย่างเดียว.

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

**คืนค่า:**
android.graphics.PointF[]