---
title: MathFunctionFactory
second_title: Aspose.Slides for Java API 參考
description: 允許建立數學函式
type: docs
url: /zh-hant/com.aspose.slides/mathfunctionfactory/
---
**繼承：**
java.lang.Object

**已實作的介面：**
[com.aspose.slides.IMathFunctionFactory](../../com.aspose.slides/imathfunctionfactory)
```
public class MathFunctionFactory implements IMathFunctionFactory
```

允許建立數學函式

--------------------

用於 COM 相容性
## 建構式

| 建構式 | 描述 |
| --- | --- |
| [MathFunctionFactory()](#MathFunctionFactory--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 建立數學函式 |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | 建立數學函式 |
### MathFunctionFactory() {#MathFunctionFactory--}
```
public MathFunctionFactory()
```


### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```


建立數學函式

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | 用作函式名稱的元素 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 用作函式參數的元素 |

**傳回值：**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新的數學函式
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


建立數學函式

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| funcName | java.lang.String | 函式名稱 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 用作函式參數的元素 |

**傳回值：**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新的數學函式