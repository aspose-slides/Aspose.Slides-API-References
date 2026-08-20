---
title: InkTrace
second_title: Aspose.Slides for Java API 參考
description: 表示一個 Trace 物件。
type: docs
url: /zh-hant/com.aspose.slides/inktrace/
---
**繼承:**  
java.lang.Object

**所有實作的介面:**  
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)  
```
public class InkTrace implements IInkTrace
```

代表一個 Trace 物件。Trace 元素用於記錄由 digitizer 捕獲的資料。它包含一系列依據 InkTraceFormat 物件所提供的規範編碼的點。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getBrush()](#getBrush--) | 取得 IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) 的 Brush（唯讀）。 |
| [getPoints()](#getPoints--) | 取得 IInkLine java.awt.geom.Point2D.Float 的點（唯讀）。 |
### getBrush() {#getBrush--}
```
public final IInkBrush getBrush()
```

取得 IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) 的 Brush（唯讀）。

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

**返回:**  
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public final Point2D.Float[] getPoints()
```

取得 IInkLine java.awt.geom.Point2D.Float 的點（唯讀）。

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

**返回:**  
java.awt.geom.Point2D.Float[]