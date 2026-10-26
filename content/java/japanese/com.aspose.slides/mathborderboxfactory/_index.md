---
title: MathBorderBoxFactory
second_title: Aspose.Slides for Java API リファレンス
description: 数式の境界ボックスを作成できます
type: docs
url: /ja/com.aspose.slides/mathborderboxfactory/
---
**継承:**
java.lang.Object

**実装しているすべてのインターフェイス:**
[com.aspose.slides.IMathBorderBoxFactory](../../com.aspose.slides/imathborderboxfactory)
```
public class MathBorderBoxFactory implements IMathBorderBoxFactory
```

数式の境界ボックスを作成できます

--------------------

COM 互換性のため
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MathBorderBoxFactory()](#MathBorderBoxFactory--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | 数式の要素に適用して境界ボックスを作成します |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | 数式の要素に適用して境界ボックスを作成します |
### MathBorderBoxFactory() {#MathBorderBoxFactory--}
```
public MathBorderBoxFactory()
```

### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element)
```

数式の要素に適用して境界ボックスを作成します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 境界ボックスを適用する数式要素 |

**戻り値:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 新しい境界ボックス要素
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

数式の要素に適用して境界ボックスを作成します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 境界ボックスを適用する数式要素 |
| hideTop | boolean | 上端を非表示 |
| hideBottom | boolean | 下端を非表示 |
| hideLeft | boolean | 左端を非表示 |
| hideRight | boolean | 右端を非表示 |
| strikethroughHorizontal | boolean | 境界ボックスの水平取り消し線 |
| strikethroughVertical | boolean | 境界ボックスの垂直取り消し線 |
| strikethroughBottomLeftToTopRight | boolean | 境界ボックスの左下から右上への取り消し線 |
| strikethroughTopLeftToBottomRight | boolean | 境界ボックスの左上から右下への取り消し線 |

**戻り値:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 新しい境界ボックス要素