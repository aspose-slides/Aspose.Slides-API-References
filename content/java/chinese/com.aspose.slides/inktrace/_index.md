---
title: InkTrace
second_title: Aspose.Slides for Java API 参考
description: 表示一个 Trace 对象。
type: docs
url: /zh/com.aspose.slides/inktrace/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)
```
public class InkTrace implements IInkTrace
```

表示一个 Trace 对象。Trace 元素用于记录数字化仪捕获的数据。它包含一系列根据 InkTraceFormat 对象提供的规范编码的点。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getBrush()](#getBrush--) | 获取 IInkLine 的 Brush [IInkBrush](../../com.aspose.slides/iinkbrush) 只读。 |
| [getPoints()](#getPoints--) | 获取 IInkLine 的 points java.awt.geom.Point2D.Float 只读。 |

### getBrush() {#getBrush--}
```
public final IInkBrush getBrush()
```

获取 IInkLine 的 Brush [IInkBrush](../../com.aspose.slides/iinkbrush) 只读。

---

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


**返回：**
[IInkBrush](../../com.aspose.slides/iinkbrush)

### getPoints() {#getPoints--}
```
public final Point2D.Float[] getPoints()
```

获取 IInkLine 的 points java.awt.geom.Point2D.Float 只读。

---

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


**返回：**
java.awt.geom.Point2D.Float[]