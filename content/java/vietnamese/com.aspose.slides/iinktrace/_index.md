---
title: IInkTrace
second_title: Aspose.Slides for Java API Reference
description: Biểu diễn đường viết tay trong một đối tượng Ink.
type: docs
url: /vi/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

Biểu diễn đường viết tay trong một đối tượng Ink.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getBrush()](#getBrush--) | Lấy Brush cho IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) chỉ đọc. |
| [getPoints()](#getPoints--) | Lấy các điểm cho IInkLine java.awt.geom.Point2D.Float chỉ đọc. |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```

Lấy Brush cho IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) chỉ đọc.

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

**Trả về:**  
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public abstract Point2D.Float[] getPoints()
```

Lấy các điểm cho IInkLine java.awt.geom.Point2D.Float chỉ đọc.

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

**Trả về:**  
java.awt.geom.Point2D.Float[]