---
title: IMathFunctionFactory
second_title: Aspose.Slides 适用于 Android 的 Java API 参考
description: 允许创建数学函数
type: docs
url: /zh/com.aspose.slides/imathfunctionfactory/
---```
public interface IMathFunctionFactory
```

允许创建数学函数

--------------------

用于 COM 兼容性
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 创建数学函数 |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | 创建数学函数 |
### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```

创建数学函数

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | 用作函数名称的元素 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 用作函数参数的元素 |

**返回:**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新的数学函数
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```

创建数学函数

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| funcName | java.lang.String | 函数名称 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 用作函数参数的元素 |

**返回:**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新的数学函数