---
title: IMathBorderBoxFactory
second_title: Aspose.Slides for Java API Reference
description: 允許建立數學邊框盒
type: docs
url: /zh-hant/com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

允許建立數學邊框盒

--------------------

供 COM 相容性
## 方法

| 方法 | 說明 |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Create a math border box by applying to the element |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Create a math border box by applying to the element |
### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element)
```

透過套用到元素來建立數學邊框盒

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 套用邊框盒的數學元素 |

**傳回值：**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 新的邊框盒元素
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

透過套用到元素來建立數學邊框盒

**參數：**
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

**傳回值：**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 新的邊框盒元素