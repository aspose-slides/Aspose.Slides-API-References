---
title: IInkBrush
second_title: Aspose.Slides for Android の Java API リファレンス
description: トレースブラシを表します。
type: docs
url: /ja/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

トレースブラシを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getColor()](#getColor--) | 線のブラシ色を取得または設定します。 |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | 線のブラシ色を取得または設定します。 |
| [getSize()](#getSize--) | 線のブラシサイズをポイント単位で取得または設定します。 |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | 線のブラシサイズをポイント単位で取得または設定します。 |
| [getInkEffect()](#getInkEffect--) | インクストロークの視覚スタイルを定義するインク効果タイプ（例: Galaxy、Gold、Silver）です。 |
### getColor() {#getColor--}
```
public abstract Integer getColor()
```


線のブラシ色を取得または設定します。

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
public abstract void setColor(Integer value)
```


線のブラシ色を取得または設定します。

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

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getSize() {#getSize--}
```
public abstract SizeF getSize()
```


線のブラシサイズをポイント単位で取得または設定します。

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
public abstract void setSize(SizeF value)
```


線のブラシサイズをポイント単位で取得または設定します。

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

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.slides.android/sizef) |  |

### getInkEffect() {#getInkEffect--}
```
public abstract int getInkEffect()
```


インクストロークの視覚スタイルを定義するインク効果タイプ（例: Galaxy、Gold、Silver）です。この値はブラシプロパティ "inkEffects" から解析されます。認識可能な効果が指定されていない場合、[InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) が返されます。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      Ink ink = (Ink) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkBrush brush = ink.getTraces()[0].getBrush();
>      System.out.println("InkEffects = " + brush.getInkEffect());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
int