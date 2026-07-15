---
title: MathBorderBoxFactory
second_title: Aspose.Slides for Android via Java API 參考
description: 允許建立數學邊框盒
type: docs
url: /zh-hant/com.aspose.slides/mathborderboxfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IMathBorderBoxFactory](../../com.aspose.slides/imathborderboxfactory)
```
public class MathBorderBoxFactory implements IMathBorderBoxFactory
```

允許建立數學邊框盒

--------------------

供 COM 相容性
## 建構函式

| 建構函式 | 描述 |
| --- | --- |
| [MathBorderBoxFactory()](#MathBorderBoxFactory--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | 透過套用於元素來建立數學邊框盒 |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | 透過套用於元素來建立數學邊框盒 |
### MathBorderBoxFactory() {#MathBorderBoxFactory--}
```
public MathBorderBoxFactory()
```


### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element)
```

透過套用於元素來建立數學邊框盒

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 套用於邊框盒的數學元素 |

**回傳:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 新的邊框盒元素

### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

透過套用於元素來建立數學邊框盒

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 套用於邊框盒的數學元素 |
| hideTop | boolean | 隱藏上緣 |
| hideBottom | boolean | 隱藏下緣 |
| hideLeft | boolean | 隱藏左緣 |
| hideRight | boolean | 隱藏右緣 |
| strikethroughHorizontal | boolean | 邊框盒水平刪除線 |
| strikethroughVertical | boolean | 邊框盒垂直刪除線 |
| strikethroughBottomLeftToTopRight | boolean | 邊框盒從左下至右上刪除線 |
| strikethroughTopLeftToBottomRight | boolean | 邊框盒從左上至右下刪除線 |

**回傳:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 新的邊框盒元素