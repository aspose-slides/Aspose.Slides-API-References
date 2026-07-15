---
title: InkTrace
second_title: Aspose.Slides 針對 Android 的 Java API 參考
description: 表示一個 Trace 物件。
type: docs
url: /zh-hant/com.aspose.slides/inktrace/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)
```
public class InkTrace implements IInkTrace
```

表示一個 Trace 物件。Trace 元素用於記錄數位化儀所捕獲的資料。它包含一系列依據 InkTraceFormat 物件所提供的規範編碼的點。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getBrush()](#getBrush--) | 取得 Brush 供 IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) 唯讀。 |
| [getPoints()](#getPoints--) | 取得 points 供 IInkLine android.graphics.PointF 唯讀。 |

### getBrush() {#getBrush--}
```
public final IInkBrush getBrush()
```

取得 Brush 供 IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) 唯讀。

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

**返回：** [IInkBrush](../../com.aspose.slides/iinkbrush)

### getPoints() {#getPoints--}
```
public final PointF[] getPoints()
```

取得 points 供 IInkLine android.graphics.PointF 唯讀。

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

**返回：** android.graphics.PointF[]