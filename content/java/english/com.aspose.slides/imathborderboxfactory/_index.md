---
title: IMathBorderBoxFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math border box
type: docs
weight: 891
url: /com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

Allows to create a math border box

--------------------

For COM comparibility
## Methods

| Method | Description |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Create a math border box by applying to the element |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Create a math border box by applying to the element |
### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element)
```


Create a math border box by applying to the element

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | math element to apply border box |

**Returns:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - new border box element
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


Create a math border box by applying to the element

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | math element to apply border box |
| hideTop | boolean | Hide Top Edge |
| hideBottom | boolean | Hide Bottom Edge |
| hideLeft | boolean | Hide Left Edge |
| hideRight | boolean | Hide Right Edge |
| strikethroughHorizontal | boolean | Border Box Strikethrough Horizontal |
| strikethroughVertical | boolean | Border Box Strikethrough Vertical |
| strikethroughBottomLeftToTopRight | boolean | Border Box Strikethrough Bottom-Left to Top-Right |
| strikethroughTopLeftToBottomRight | boolean | Border Box Strikethrough Top-Left to Bottom-Right |

**Returns:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - new border box element
