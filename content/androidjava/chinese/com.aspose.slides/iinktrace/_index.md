---
title: IInkTrace
second_title: Aspose.Slides for Android via Java API 参考
description: 表示 Ink 对象中的手写线。
type: docs
url: /zh/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

表示 Ink 对象中的手写线。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBrush()](#getBrush--) | 获取 IInkLine 的 Brush [IInkBrush](../../com.aspose.slides/iinkbrush) 只读。 |
| [getPoints()](#getPoints--) | 获取 IInkLine 的 points，android.graphics.PointF，只读。 |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```

获取 IInkLine 的 Brush [IInkBrush](../../com.aspose.slides/iinkbrush) 只读。

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

获取 IInkLine 的 points，android.graphics.PointF，只读。

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

**返回：**
android.graphics.PointF[]