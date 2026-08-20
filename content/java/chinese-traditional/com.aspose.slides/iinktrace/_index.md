---
title: IInkTrace
second_title: Aspose.Slides for Java API Reference
description: 代表 Ink 物件中的手寫線條。
type: docs
url: /zh-hant/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

代表 Ink 物件中的手寫線條。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBrush()](#getBrush--) | 取得 IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) 的 Brush，唯讀。 |
| [getPoints()](#getPoints--) | 取得 IInkLine java.awt.geom.Point2D.Float 的點，唯讀。 |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```


取得 IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) 的 Brush，唯讀。

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

**傳回：**
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public abstract Point2D.Float[] getPoints()
```


取得 IInkLine java.awt.geom.Point2D.Float 的點，唯讀。

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

**傳回：**
java.awt.geom.Point2D.Float[]