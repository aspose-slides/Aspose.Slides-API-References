---
title: InkTrace
second_title: Tham khảo API Java qua Aspose.Slides cho Android
description: Biểu diễn một đối tượng Trace.
type: docs
url: /vi/com.aspose.slides/inktrace/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)
```
public class InkTrace implements IInkTrace
```

Biểu diễn một đối tượng Trace. Một phần tử Trace được dùng để ghi lại dữ liệu được số hoá bởi thiết bị digitizer. Nó chứa một chuỗi các điểm được mã hoá theo đặc tả được cung cấp bởi đối tượng InkTraceFormat.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getBrush()](#getBrush--) | Lấy Brush cho IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) chỉ đọc. |
| [getPoints()](#getPoints--) | Lấy các điểm cho IInkLine android.graphics.PointF chỉ đọc. |
### getBrush() {#getBrush--}
```
public final IInkBrush getBrush()
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
public final PointF[] getPoints()
```


Lấy các điểm cho IInkLine android.graphics.PointF chỉ đọc.

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