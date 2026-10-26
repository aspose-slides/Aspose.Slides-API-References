---
title: MathBorderBoxFactory
second_title: Java API リファレンスによる Android 向け Aspose.Slides
description: 数式のボーダーボックスを作成できます
type: docs
url: /ja/com.aspose.slides/mathborderboxfactory/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IMathBorderBoxFactory](../../com.aspose.slides/imathborderboxfactory)
```
public class MathBorderBoxFactory implements IMathBorderBoxFactory
```

数式のボーダーボックスを作成できます

--------------------

COM 互換性のため
## コンストラクター

| Constructor | 説明 |
| --- | --- |
| [MathBorderBoxFactory()](#MathBorderBoxFactory--) |  |
## メソッド

| Method | 説明 |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | 要素に適用して数式のボーダーボックスを作成します |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | 要素に適用して数式のボーダーボックスを作成します |
### MathBorderBoxFactory() {#MathBorderBoxFactory--}
```
public MathBorderBoxFactory()
```

### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element)
```

要素に適用して数式のボーダーボックスを作成します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | ボーダーボックスを適用する数式要素 |

**戻り値:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 新しいボーダーボックス要素
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

要素に適用して数式のボーダーボックスを作成します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | ボーダーボックスを適用する数式要素 |
| hideTop | boolean | 上端を非表示 |
| hideBottom | boolean | 下端を非表示 |
| hideLeft | boolean | 左端を非表示 |
| hideRight | boolean | 右端を非表示 |
| strikethroughHorizontal | boolean | 水平ストライクスルー ボーダーボックス |
| strikethroughVertical | boolean | 垂直ストライクスルー ボーダーボックス |
| strikethroughBottomLeftToTopRight | boolean | 左下から右上へのストライクスルー ボーダーボックス |
| strikethroughTopLeftToBottomRight | boolean | 左上から右下へのストライクスルー ボーダーボックス |

**戻り値:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 新しいボーダーボックス要素