---
title: InkTrace
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一个 Trace 对象。
type: docs
url: /zh/com.aspose.slides/inktrace/
---
**继承：**
java.lang.Object

**实现的所有接口：**
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)
```
public class InkTrace implements IInkTrace
```

表示一个 Trace 对象。Trace 元素用于记录数字化仪捕获的数据。它包含一系列点，这些点根据 InkTraceFormat 对象提供的规范进行编码。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBrush()](#getBrush--) | 获取 IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) 的 Brush。只读。 |
| [getPoints()](#getPoints--) | 获取 IInkLine android.graphics.PointF 的点。只读。 |
### getBrush() {#getBrush--}
```
public final IInkBrush getBrush()
```


获取 IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) 的 Brush。只读。

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
public final PointF[] getPoints()


获取 IInkLine android.graphics.PointF 的点。只读。


--------------------

Example:
 
 Presentation pres = new Presentation("pres.pptx");
 try {
     IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
     IInkTrace[] traces = ink.getTraces();
     android.graphics.PointF[] points = traces[0].getPoints();
 } finally {
     if (pres != null) pres.dispose();
 }

**返回值：**
android.graphics.PointF[]