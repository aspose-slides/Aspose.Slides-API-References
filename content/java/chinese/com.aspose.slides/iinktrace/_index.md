---
title: IInkTrace
second_title: Aspose.Slides for Java API 参考
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
| [getBrush()](#getBrush--) | 获取 IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) 的 Brush，只读。 |
| [getPoints()](#getPoints--) | 获取 IInkLine java.awt.geom.Point2D.Float 的点，只读。 |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```


获取 IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) 的 Brush，只读。

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

**返回：**
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public abstract Point2D.Float[] getPoints()
```


获取 IInkLine java.awt.geom.Point2D.Float 的点，只读。

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

**返回：**
java.awt.geom.Point2D.Float[]