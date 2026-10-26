---
title: IMathBorderBoxFactory
second_title: Aspose.Slides for Android via Java API 參考
description: 允許建立數學邊框盒
type: docs
url: /zh-hant/com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

允許建立數學邊框盒

--------------------

用於 COM 相容性
## 方法

| 方法 | 說明 |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | 透過套用於元素來建立數學邊框盒 |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | 透過套用於元素來建立數學邊框盒 |
### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element)
```


建立數學邊框盒，套用於元素

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 套用邊框盒的數學元素 |

**傳回值:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 新的邊框盒元素
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


建立數學邊框盒，套用於元素

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 套用邊框盒的數學元素 |
| hideTop | boolean | 隱藏上邊緣 |
| hideBottom | boolean | 隱藏下邊緣 |
| hideLeft | boolean | 隱藏左邊緣 |
| hideRight | boolean | 隱藏右邊緣 |
| strikethroughHorizontal | boolean | 水平刪除線的邊框盒 |
| strikethroughVertical | boolean | 垂直刪除線的邊框盒 |
| strikethroughBottomLeftToTopRight | boolean | 從左下至右上刪除線的邊框盒 |
| strikethroughTopLeftToBottomRight | boolean | 從左上至右下刪除線的邊框盒 |

**傳回值:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 新的邊框盒元素