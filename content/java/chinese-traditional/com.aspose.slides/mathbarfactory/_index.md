---
title: MathBarFactory
second_title: Aspose.Slides for Java API 參考
description: 允許建立數學上橫線
type: docs
url: /zh-hant/com.aspose.slides/mathbarfactory/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.IMathBarFactory](../../com.aspose.slides/imathbarfactory)
```
public class MathBarFactory implements IMathBarFactory
```

允許建立數學上橫線

--------------------

適用於 COM 相容性
## 建構子

| 建構子 | 說明 |
| --- | --- |
| [MathBarFactory()](#MathBarFactory--) |  |
## 方法

| 方法 | 說明 |
| --- | --- |
| [createMathBar(IMathElement element)](#createMathBar-com.aspose.slides.IMathElement-) | Create a math bar by applying to the element |
| [createMathBar(IMathElement element, int position)](#createMathBar-com.aspose.slides.IMathElement-int-) | Create a math bar by applying to the element |
### MathBarFactory() {#MathBarFactory--}
```
public MathBarFactory()
```


### createMathBar(IMathElement element) {#createMathBar-com.aspose.slides.IMathElement-}
```
public final IMathBar createMathBar(IMathElement element)
```

透過套用於元素建立數學上橫線

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 要套用上橫線的數學元素 |

**回傳值：**
[IMathBar](../../com.aspose.slides/imathbar) - 新的數學上橫線元素
### createMathBar(IMathElement element, int position) {#createMathBar-com.aspose.slides.IMathElement-int-}
```
public final IMathBar createMathBar(IMathElement element, int position)
```

透過套用於元素建立數學上橫線

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 要套用上橫線的數學元素 |
| position | int | 上橫線的位置 |

**回傳值：**
[IMathBar](../../com.aspose.slides/imathbar) - 新的數學上橫線元素