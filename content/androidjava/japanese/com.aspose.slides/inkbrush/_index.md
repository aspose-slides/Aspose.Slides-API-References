---
title: InkBrush
second_title: Java API リファレンスによる Aspose.Slides for Android
description: inkBrush オブジェクトを表します。
type: docs
url: /ja/com.aspose.slides/inkbrush/
---
**継承:**  
java.lang.Object

**実装されたすべてのインターフェイス:**  
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)  
```
public class InkBrush implements IInkBrush
```

inkBrush オブジェクトを表します。  
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getColor()](#getColor--) | ラインのブラシカラーを取得または設定します。 |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | ラインのブラシカラーを取得または設定します。 |
| [getSize()](#getSize--) | ラインのブラシサイズ（ポイント単位）を取得または設定します。 |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | ラインのブラシサイズ（ポイント単位）を取得または設定します。 |
| [getInkEffect()](#getInkEffect--) | インクストロークの視覚的スタイルを定義するインク効果タイプ（例: Galaxy、Gold、Silver）を取得します。 |

### getColor() {#getColor--}
```
public final Integer getColor()
```

ラインのブラシカラーを取得または設定します。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Color brushColor = brush.getColor();
>      brush.setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**  
java.lang.Integer

### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public final void setColor(Integer value)
```

ラインのブラシカラーを取得または設定します。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Color brushColor = brush.getColor();
>      brush.setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getSize() {#getSize--}
```
public final SizeF getSize()
```

ラインのブラシサイズ（ポイント単位）を取得または設定します。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      SizeF brushSize = brush.getSize();
>      brush.setSize(new com.aspose.slides.android.Size(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**  
[SizeF](../../com.aspose.slides.android/sizef)

### setSize(SizeF value) {#setSize-com.aspose.slides.android.SizeF-}
```
public final void setSize(SizeF value)
```

ラインのブラシサイズ（ポイント単位）を取得または設定します。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      SizeF brushSize = brush.getSize();
>      brush.setSize(new com.aspose.slides.android.Size(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.slides.android/sizef) |  |

### getInkEffect() {#getInkEffect--}
```
public final int getInkEffect()
```

インクストロークの視覚的スタイルを定義するインク効果タイプ（例: Galaxy、Gold、Silver）を取得します。ブラシプロパティ "inkEffects" から値が解析されます。認識された効果が指定されていない場合、[InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) が返されます。

**戻り値:**  
int