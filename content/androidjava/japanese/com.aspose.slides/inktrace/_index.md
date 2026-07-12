---
title: InkTrace
second_title: Java API リファレンスによる Aspose.Slides for Android
description: Trace オブジェクトを表します。
type: docs
url: /ja/com.aspose.slides/inktrace/
---
**継承:**
java.lang.Object

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)
```
public class InkTrace implements IInkTrace
```

Trace オブジェクトを表します。Trace 要素はデジタイザによって取得されたデータを記録するために使用されます。InkTraceFormat オブジェクトが提供する仕様に従ってエンコードされたポイントのシーケンスを含みます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBrush()](#getBrush--) | IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) の Brush を取得します (読み取り専用)。 |
| [getPoints()](#getPoints--) | IInkLine android.graphics.PointF のポイントを取得します (読み取り専用)。 |
### getBrush() {#getBrush--}
```
public final IInkBrush getBrush()
```


IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) の Brush を取得します (読み取り専用)。

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
public final PointF[] getPoints()
```


IInkLine android.graphics.PointF のポイントを取得します (読み取り専用)。

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