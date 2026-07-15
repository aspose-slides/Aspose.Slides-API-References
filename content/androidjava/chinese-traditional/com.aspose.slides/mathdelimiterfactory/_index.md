---
title: MathDelimiterFactory
second_title: Aspose.Slides for Android via Java API 參考
description: 允許建立數學分隔符
type: docs
url: /zh-hant/com.aspose.slides/mathdelimiterfactory/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.IMathDelimiterFactory](../../com.aspose.slides/imathdelimiterfactory)
```
public class MathDelimiterFactory implements IMathDelimiterFactory
```

允許建立數學分隔符

--------------------

供 COM 相容性
## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [MathDelimiterFactory()](#MathDelimiterFactory--) |  |
## 方法

| 方法 | 說明 |
| --- | --- |
| [createMathDelimiter(IMathElement element)](#createMathDelimiter-com.aspose.slides.IMathElement-) | 透過套用於元素來建立數學分隔符 |
| [createMathDelimiter(IMathElementCollection mathElements)](#createMathDelimiter-com.aspose.slides.IMathElementCollection-) | 透過套用於元素來建立數學分隔符 |
### MathDelimiterFactory() {#MathDelimiterFactory--}
```
public MathDelimiterFactory()
```


### createMathDelimiter(IMathElement element) {#createMathDelimiter-com.aspose.slides.IMathElement-}
```
public final IMathDelimiter createMathDelimiter(IMathElement element)
```


透過套用於元素來建立數學分隔符

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 套用分隔符的數學元素 |

**傳回值：**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 新的數學分隔符
### createMathDelimiter(IMathElementCollection mathElements) {#createMathDelimiter-com.aspose.slides.IMathElementCollection-}
```
public final IMathDelimiter createMathDelimiter(IMathElementCollection mathElements)
```


透過套用於元素來建立數學分隔符

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | 套用分隔符的數學元素集合 |

**傳回值：**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 新的數學分隔符