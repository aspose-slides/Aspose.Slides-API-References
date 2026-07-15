---
title: MathNaryOperatorFactory
second_title: Aspose.Slides for Android 之 Java API 參考
description: 允許建立 IMathNaryOperator
type: docs
url: /zh-hant/com.aspose.slides/mathnaryoperatorfactory/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.IMathNaryOperatorFactory](../../com.aspose.slides/imathnaryoperatorfactory)
```
public class MathNaryOperatorFactory implements IMathNaryOperatorFactory
```

允許建立 IMathNaryOperator

--------------------

適用於 COM 相容性
## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [MathNaryOperatorFactory()](#MathNaryOperatorFactory--) |  |
## 方法

| 方法 | 說明 |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 建立 IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 建立 IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | 建立 IMathNaryOperator |
### MathNaryOperatorFactory() {#MathNaryOperatorFactory--}
```
public MathNaryOperatorFactory()
```

### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

建立 IMathNaryOperator

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| operatorSymbol | char | 運算子符號 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 用於套用運算子的基礎引數 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 下限 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 上限 |

**傳回值：**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 新的 IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

建立 IMathNaryOperator

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| operatorSymbol | char | 運算子符號 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 用於套用運算子的基礎引數 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 下限 |

**傳回值：**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 新的 IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

建立 IMathNaryOperator

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| operatorSymbol | char | 運算子符號 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 用於套用運算子的基礎引數 |

**傳回值：**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 新的 IMathNaryOperator