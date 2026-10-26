---
title: MathFunctionFactory
second_title: Aspose.Slides for Android 之 Java API 參考
description: 允許建立數學函式
type: docs
url: /zh-hant/com.aspose.slides/mathfunctionfactory/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.IMathFunctionFactory](../../com.aspose.slides/imathfunctionfactory)
```
public class MathFunctionFactory implements IMathFunctionFactory
```

允許建立數學函式

--------------------

供 COM 相容性使用
## 建構函式

| Constructor | Description |
| --- | --- |
| [MathFunctionFactory()](#MathFunctionFactory--) |  |
## 方法

| Method | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | 用作函式名稱的元素 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 用作函式參數的元素 |

**回傳值：**
[IMathFunction](../../com.aspose.slides/imathfunction) - new math function
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


建立數學函式

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| funcName | java.lang.String | 函式名稱 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 用作函式參數的元素 |

**回傳值：**
[IMathFunction](../../com.aspose.slides/imathfunction) - new math function