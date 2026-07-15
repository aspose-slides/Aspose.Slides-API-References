---
title: IMathBarFactory
second_title: Aspose.Slides for Android via Java API Reference
description: 允許建立數學上標
type: docs
url: /zh-hant/com.aspose.slides/imathbarfactory/
---```
public interface IMathBarFactory
```

允許建立數學上標

--------------------

用於 COM 相容性
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathBar(IMathElement element)](#createMathBar-com.aspose.slides.IMathElement-) | 透過套用於元素來建立數學上標 |
| [createMathBar(IMathElement element, int position)](#createMathBar-com.aspose.slides.IMathElement-int-) | 透過套用於元素來建立數學上標 |
### createMathBar(IMathElement element) {#createMathBar-com.aspose.slides.IMathElement-}
```
public abstract IMathBar createMathBar(IMathElement element)
```


透過套用於元素來建立數學上標

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 用於套用上標的數學元素 |

**回傳:**
[IMathBar](../../com.aspose.slides/imathbar) - 新的數學上標元素
### createMathBar(IMathElement element, int position) {#createMathBar-com.aspose.slides.IMathElement-int-}
```
public abstract IMathBar createMathBar(IMathElement element, int position)
```


透過套用於元素來建立數學上標

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 用於套用上標的數學元素 |
| position | int | 上標的位置 |

**回傳:**
[IMathBar](../../com.aspose.slides/imathbar) - 新的數學上標元素