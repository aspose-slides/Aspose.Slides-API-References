---
title: IInkTrace
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn đường vẽ tay trong một đối tượng Ink.
type: docs
url: /vi/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

Biểu diễn đường vẽ tay trong một đối tượng Ink.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getBrush()](#getBrush--) | Lấy Brush cho IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Chỉ đọc. |
| [getPoints()](#getPoints--) | Lấy các điểm cho IInkLine android.graphics.PointF Chỉ đọc. |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```


Lấy Brush cho IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) Chỉ đọc.

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
public abstract PointF[] getPoints()
```


Lấy các điểm cho IInkLine android.graphics.PointF Chỉ đọc.

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

**Trả về:**  
android.graphics.PointF[]