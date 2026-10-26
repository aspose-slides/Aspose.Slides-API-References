---
title: IMathNaryOperatorFactory
second_title: Aspose.Slides for Android via Java API 參考
description: 允許建立 IMathNaryOperator
type: docs
url: /zh-hant/com.aspose.slides/imathnaryoperatorfactory/
---```
public interface IMathNaryOperatorFactory
```

允許建立 IMathNaryOperator

--------------------

針對 COM 相容性
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 建立 IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 建立 IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | 建立 IMathNaryOperator |
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


建立 IMathNaryOperator

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| operatorSymbol | char | 運算子符號 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 用於套用運算子的基礎參數 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 下限 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 上限 |

**傳回值：**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 新的 IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


建立 IMathNaryOperator

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| operatorSymbol | char | 運算子符號 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 用於套用運算子的基礎參數 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 下限 |

**傳回值：**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 新的 IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


建立 IMathNaryOperator

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| operatorSymbol | char | 運算子符號 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 用於套用運算子的基礎參數 |

**傳回值：**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 新的 IMathNaryOperator