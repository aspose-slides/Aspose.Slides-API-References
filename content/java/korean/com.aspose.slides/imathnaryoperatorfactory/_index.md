---
title: IMathNaryOperatorFactory
second_title: Aspose.Slides for Java API Reference
description: IMathNaryOperator 를 생성할 수 있습니다
type: docs
url: /ko/com.aspose.slides/imathnaryoperatorfactory/
---```
public interface IMathNaryOperatorFactory
```

IMathNaryOperator 를 생성할 수 있습니다

--------------------

COM 호환성을 위해
## Methods

| Method | Description |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | IMathNaryOperator 를 생성합니다 |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | IMathNaryOperator 를 생성합니다 |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | IMathNaryOperator 를 생성합니다 |
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

IMathNaryOperator 를 생성합니다

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| operatorSymbol | char | 연산자 기호 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 연산자를 적용할 기본 인수 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 하한 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 상한 |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 새 IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

IMathNaryOperator 를 생성합니다

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| operatorSymbol | char | 연산자 기호 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 연산자를 적용할 기본 인수 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 하한 |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 새 IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

IMathNaryOperator 를 생성합니다

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| operatorSymbol | char | 연산자 기호 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 연산자를 적용할 기본 인수 |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 새 IMathNaryOperator