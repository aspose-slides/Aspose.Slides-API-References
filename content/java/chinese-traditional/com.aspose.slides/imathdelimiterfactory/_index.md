---
title: IMathDelimiterFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math delimiter
type: docs
url: /zh-hant/com.aspose.slides/imathdelimiterfactory/
---```
public interface IMathDelimiterFactory
```

允許建立數學分隔符

--------------------

供 COM 相容性
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathDelimiter(IMathElement element)](#createMathDelimiter-com.aspose.slides.IMathElement-) | 建立數學分隔符，套用於元素 |
| [createMathDelimiter(IMathElementCollection mathElements)](#createMathDelimiter-com.aspose.slides.IMathElementCollection-) | 建立數學分隔符，套用於元素 |
### createMathDelimiter(IMathElement element) {#createMathDelimiter-com.aspose.slides.IMathElement-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElement element)
```


建立數學分隔符，套用於元素

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 套用分隔符的數學元素 |

**返回值：**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 新的數學分隔符
### createMathDelimiter(IMathElementCollection mathElements) {#createMathDelimiter-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElementCollection mathElements)
```


建立數學分隔符，套用於元素

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | 套用分隔符的數學元素 |

**返回值：**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 新的數學分隔符