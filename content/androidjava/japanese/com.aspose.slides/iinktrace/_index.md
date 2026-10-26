---
title: IInkTrace
second_title: Aspose.Slides Android 用 Java API リファレンス
description: Ink オブジェクト内の手書きラインを表します。
type: docs
url: /ja/com.aspose.slides/iinktrace/
---```
public interface IInkTrace
```

Ink オブジェクト内の手書きラインを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBrush()](#getBrush--) | IInkLine の Brush を取得します [IInkBrush](../../com.aspose.slides/iinkbrush) 読み取り専用。 |
| [getPoints()](#getPoints--) | IInkLine のポイント (android.graphics.PointF) を取得します 読み取り専用。 |
### getBrush() {#getBrush--}
```
public abstract IInkBrush getBrush()
```


IInkLine の Brush を取得します [IInkBrush](../../com.aspose.slides/iinkbrush) 読み取り専用。

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


**戻り値:**
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public abstract PointF[] getPoints()
```


IInkLine のポイント (android.graphics.PointF) を取得します 読み取り専用。

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

**戻り値:**
android.graphics.PointF[]