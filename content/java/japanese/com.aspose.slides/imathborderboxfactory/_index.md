---
title: IMathBorderBoxFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math border box
type: docs
url: /ja/com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

数式境界ボックスの作成を可能にします

--------------------

COM 互換性のため
## メソッド

| Method | Description |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | 要素に適用して数式境界ボックスを作成します |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | 要素に適用して数式境界ボックスを作成します |
### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element)
```


要素に適用して数式境界ボックスを作成します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 境界ボックスを適用する数式要素 |

**Returns:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 新しい境界ボックス要素
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


要素に適用して数式境界ボックスを作成します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 境界ボックスを適用する数式要素 |
| hideTop | boolean | 上端を非表示にする |
| hideBottom | boolean | 下端を非表示にする |
| hideLeft | boolean | 左端を非表示にする |
| hideRight | boolean | 右端を非表示にする |
| strikethroughHorizontal | boolean | 境界ボックスの水平取り消し線 |
| strikethroughVertical | boolean | 境界ボックスの垂直取り消し線 |
| strikethroughBottomLeftToTopRight | boolean | 境界ボックスの左下から右上への取り消し線 |
| strikethroughTopLeftToBottomRight | boolean | 境界ボックスの左上から右下への取り消し線 |

**Returns:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 新しい境界ボックス要素