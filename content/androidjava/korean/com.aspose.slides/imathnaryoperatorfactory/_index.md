---
title: IMathNaryOperatorFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create IMathNaryOperator
type: docs
url: /ko/com.aspose.slides/imathnaryoperatorfactory/
---```
public interface IMathNaryOperatorFactory
```

IMathNaryOperator를 생성할 수 있습니다

--------------------

COM 호환성을 위해
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | IMathNaryOperator를 생성합니다 |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | IMathNaryOperator를 생성합니다 |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | IMathNaryOperator를 생성합니다 |
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

IMathNaryOperator를 생성합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| operatorSymbol | char | 연산자 기호 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 연산자를 적용할 기본 인수 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 하한 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 상한 |

**반환값:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 새로운 IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

IMathNaryOperator를 생성합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| operatorSymbol | char | 연산자 기호 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 연산자를 적용할 기본 인수 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 하한 |

**반환값:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 새로운 IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

IMathNaryOperator를 생성합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| operatorSymbol | char | 연산자 기호 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 연산자를 적용할 기본 인수 |

**반환값:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 새로운 IMathNaryOperator