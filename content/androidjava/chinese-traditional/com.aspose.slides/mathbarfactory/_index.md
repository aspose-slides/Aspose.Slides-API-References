---
title: MathBarFactory
second_title: 適用於 Android 的 Aspose.Slides Java API 參考
description: 允許建立數學上標
type: docs
url: /zh-hant/com.aspose.slides/mathbarfactory/
---
**繼承:**
java.lang.Object

**所有已實作的介面:**
[com.aspose.slides.IMathBarFactory](../../com.aspose.slides/imathbarfactory)
```
public class MathBarFactory implements IMathBarFactory
```

允許建立數學上標

--------------------

用於 COM 相容性
## 建構子

| 建構子 | 描述 |
| --- | --- |
| [MathBarFactory()](#MathBarFactory--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathBar(IMathElement element)](#createMathBar-com.aspose.slides.IMathElement-) | 透過套用於元素來建立數學上標 |
| [createMathBar(IMathElement element, int position)](#createMathBar-com.aspose.slides.IMathElement-int-) | 透過套用於元素來建立數學上標 |
### MathBarFactory() {#MathBarFactory--}
```
public MathBarFactory()
```


### createMathBar(IMathElement element) {#createMathBar-com.aspose.slides.IMathElement-}
```
public final IMathBar createMathBar(IMathElement element)
```


透過套用於元素來建立數學上標

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 要套用上標的數學元素 |

**傳回值:**
[IMathBar](../../com.aspose.slides/imathbar) - 新的數學上標元素
### createMathBar(IMathElement element, int position) {#createMathBar-com.aspose.slides.IMathElement-int-}
```
public final IMathBar createMathBar(IMathElement element, int position)
```


透過套用於元素來建立數學上標

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 要套用上標的數學元素 |
| position | int | 上標的位置 |

**傳回值:**
[IMathBar](../../com.aspose.slides/imathbar) - 新的數學上標元素