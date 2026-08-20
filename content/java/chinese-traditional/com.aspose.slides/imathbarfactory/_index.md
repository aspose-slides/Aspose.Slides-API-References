---
title: IMathBarFactory
second_title: Aspose.Slides for Java API Reference
description: 允許建立數學條形
type: docs
url: /zh-hant/com.aspose.slides/imathbarfactory/
---```
public interface IMathBarFactory
```

允許建立數學條形

--------------------

用於 COM 相容性
## 方法

| 方法 | 說明 |
| --- | --- |
| [createMathBar(IMathElement element)](#createMathBar-com.aspose.slides.IMathElement-) | 建立一個數學條形，套用於此元素 |
| [createMathBar(IMathElement element, int position)](#createMathBar-com.aspose.slides.IMathElement-int-) | 建立一個數學條形，套用於此元素 |
### createMathBar(IMathElement element) {#createMathBar-com.aspose.slides.IMathElement-}
```
public abstract IMathBar createMathBar(IMathElement element)
```

建立一個數學條形，套用於此元素

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 用於套用條形的數學元素 |

**回傳值：**
[IMathBar](../../com.aspose.slides/imathbar) - 新的數學條形元素
### createMathBar(IMathElement element, int position) {#createMathBar-com.aspose.slides.IMathElement-int-}
```
public abstract IMathBar createMathBar(IMathElement element, int position)
```

建立一個數學條形，套用於此元素

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 用於套用條形的數學元素 |
| position | int | 條形的位置 |

**回傳值：**
[IMathBar](../../com.aspose.slides/imathbar) - 新的數學條形元素