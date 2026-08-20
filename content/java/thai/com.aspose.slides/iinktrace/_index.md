---
title: IInkTrace
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงเส้นเขียนมือในวัตถุ Ink.
type: docs
url: /th/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

แสดงเส้นเขียนมือในวัตถุ Ink.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBrush()](#getBrush--) | รับ Brush สำหรับ IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) อ่านอย่างเดียว. |
| [getPoints()](#getPoints--) | รับ points สำหรับ IInkLine java.awt.geom.Point2D.Float อ่านอย่างเดียว. |
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

**ผลลัพธ์:**
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public abstract Point2D.Float[] getPoints()
```


รับ points สำหรับ IInkLine java.awt.geom.Point2D.Float อ่านอย่างเดียว.

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

**ผลลัพธ์:**
java.awt.geom.Point2D.Float[]