---
title: InkBrush
second_title: Aspose.SlidesのJava APIリファレンス
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
| [getColor()](#getColor--) | 線のブラシの色を取得または設定します。 |
| [setColor(Color value)](#setColor-java.awt.Color-) | 線のブラシの色を取得または設定します。 |
| [getSize()](#getSize--) | 線のブラシサイズをポイント単位で取得または設定します。 |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | 線のブラシサイズをポイント単位で取得または設定します。 |
| [getInkEffect()](#getInkEffect--) | インクストロークの視覚的スタイルを定義するインク効果タイプ（例: Galaxy、Gold、Silver）を取得します。 |

### getColor() {#getColor--}
```
public final Color getColor()
```

線のブラシの色を取得または設定します。

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
java.awt.Color

### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```

線のブラシの色を取得または設定します。

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
| value | java.awt.Color |  |

### getSize() {#getSize--}
```
public final Dimension2D getSize()
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
>      Dimension2D brushSize = brush.getSize();
>      brush.setSize(new Dimension(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**  
java.awt.geom.Dimension2D

### setSize(Dimension2D value) {#setSize-java.awt.geom.Dimension2D-}
```
public final void setSize(Dimension2D value)
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
>      Dimension2D brushSize = brush.getSize();
>      brush.setSize(new Dimension(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.awt.geom.Dimension2D |  |

### getInkEffect() {#getInkEffect--}
```
public final int getInkEffect()
```

インクストロークの視覚的スタイルを定義するインク効果タイプ（例: Galaxy、Gold、Silver）を取得します。この値はブラシプロパティ「inkEffects」から解析されます。認識された効果が指定されていない場合、[InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) が返されます。

**戻り値:**  
int