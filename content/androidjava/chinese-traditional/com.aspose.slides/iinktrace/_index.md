---
title: IInkTrace
second_title: Aspose.Slides for Android via Java API Reference
description: Represents handwritten line in an Ink object.
type: docs
url: /zh-hant/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

表示 Ink 物件中的手寫線條。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getBrush()](#getBrush--) | 取得 IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) 的 Brush，只讀。 |
| [getPoints()](#getPoints--) | 取得 IInkLine android.graphics.PointF 的 points，只讀。 |

### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```


取得 IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) 的 Brush，只讀。

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

**返回值:**
[IInkBrush](../../com.aspose.slides/iinkbrush)

### getPoints() {#getPoints--}
```
public abstract PointF[] getPoints()
```


取得 IInkLine android.graphics.PointF 的 points，只讀。

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

**返回值:**
android.graphics.PointF[]