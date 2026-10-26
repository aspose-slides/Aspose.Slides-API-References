---
title: MathNaryOperatorFactory
second_title: Aspose.Slides for Android via Java API 参考
description: 允许创建 IMathNaryOperator
type: docs
url: /zh/com.aspose.slides/mathnaryoperatorfactory/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.IMathNaryOperatorFactory](../../com.aspose.slides/imathnaryoperatorfactory)
```
public class MathNaryOperatorFactory implements IMathNaryOperatorFactory
```

允许创建 IMathNaryOperator

--------------------

用于 COM 兼容性
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MathNaryOperatorFactory()](#MathNaryOperatorFactory--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 创建 IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 创建 IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | 创建 IMathNaryOperator |
### MathNaryOperatorFactory() {#MathNaryOperatorFactory--}
```
public MathNaryOperatorFactory()
```


### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


创建 IMathNaryOperator

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| operatorSymbol | char | 运算符符号 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 用于应用运算符的基参数 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 下限 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 上限 |

**返回：**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 新的 IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


创建 IMathNaryOperator

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| operatorSymbol | char | 运算符符号 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 用于应用运算符的基参数 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 下限 |

**返回：**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 新的 IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


创建 IMathNaryOperator

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| operatorSymbol | char | 运算符符号 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 用于应用运算符的基参数 |

**返回：**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 新的 IMathNaryOperator