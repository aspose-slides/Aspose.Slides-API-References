---
title: MathFunctionFactory
second_title: Aspose.Slides for Android via Java API 参考
description: 允许创建数学函数
type: docs
url: /zh/com.aspose.slides/mathfunctionfactory/
---
**继承：**
java.lang.Object

**所有已实现的接口：**
[com.aspose.slides.IMathFunctionFactory](../../com.aspose.slides/imathfunctionfactory)
```
public class MathFunctionFactory implements IMathFunctionFactory
```

允许创建数学函数

--------------------

用于 COM 兼容性
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MathFunctionFactory()](#MathFunctionFactory--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 创建数学函数 |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | 创建数学函数 |
### MathFunctionFactory() {#MathFunctionFactory--}
```
public MathFunctionFactory()
```


### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```


创建数学函数

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | 用作函数名称的元素 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 用作函数参数的元素 |

**返回：**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新的数学函数
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


创建数学函数

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| funcName | java.lang.String | 函数名称 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 用作函数参数的元素 |

**返回：**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新的数学函数