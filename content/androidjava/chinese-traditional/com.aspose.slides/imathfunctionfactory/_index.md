---
title: IMathFunctionFactory
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 允許建立數學函式
type: docs
url: /zh-hant/com.aspose.slides/imathfunctionfactory/
---```
public interface IMathFunctionFactory
```

允許建立數學函式

--------------------

供 COM 相容性
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 建立數學函式 |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | 建立數學函式 |
### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```


建立數學函式

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | 用作函式名稱的元素 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 用作函式參數的元素 |

**傳回值:**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新的數學函式
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


建立數學函式

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| funcName | java.lang.String | 函式名稱 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 用作函式參數的元素 |

**傳回值:**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新的數學函式