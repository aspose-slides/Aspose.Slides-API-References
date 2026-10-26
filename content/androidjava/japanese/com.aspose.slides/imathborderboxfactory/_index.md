---
title: IMathBorderBoxFactory
second_title: Aspose.Slides for Android via Java API Reference
description: 数式のボーダーボックスを作成できます
type: docs
url: /ja/com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

数式のボーダーボックスを作成できます

--------------------

COM 互換性のため
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | 要素に適用して数式のボーダーボックスを作成します |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | 要素に適用して数式のボーダーボックスを作成します |
### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element)
```


要素に適用して数式のボーダーボックスを作成します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | ボーダーボックスを適用する数式要素 |

**戻り値:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 新しいボーダーボックス要素
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


要素に適用して数式のボーダーボックスを作成します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | ボーダーボックスを適用する数式要素 |
| hideTop | boolean | 上端を非表示 |
| hideBottom | boolean | 下端を非表示 |
| hideLeft | boolean | 左端を非表示 |
| hideRight | boolean | 右端を非表示 |
| strikethroughHorizontal | boolean | 水平の取り消し線 |
| strikethroughVertical | boolean | 垂直の取り消し線 |
| strikethroughBottomLeftToTopRight | boolean | 左下から右上への取り消し線 |
| strikethroughTopLeftToBottomRight | boolean | 左上から右下への取り消し線 |

**戻り値:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 新しいボーダーボックス要素