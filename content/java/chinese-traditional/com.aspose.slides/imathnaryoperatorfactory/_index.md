---
title: IMathNaryOperatorFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create IMathNaryOperator
type: docs
url: /zh-hant/com.aspose.slides/imathnaryoperatorfactory/
---```
public interface IMathNaryOperatorFactory
```

允許建立 IMathNaryOperator

--------------------

適用於 COM 相容性
## 方法

| 方法 | 說明 |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 建立 IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 建立 IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | 建立 IMathNaryOperator |
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

建立 IMathNaryOperator

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| operatorSymbol | char | 運算子符號 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 套用運算子的基礎參數 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 下限 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 上限 |

**返回值:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

建立 IMathNaryOperator

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| operatorSymbol | char | 運算子符號 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 套用運算子的基礎參數 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 下限 |

**返回值:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

建立 IMathNaryOperator

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| operatorSymbol | char | 運算子符號 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 套用運算子的基礎參數 |

**返回值:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator