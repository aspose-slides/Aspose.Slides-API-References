---
title: MathNaryOperatorFactory
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: IMathNaryOperator를 생성할 수 있습니다
type: docs
url: /ko/com.aspose.slides/mathnaryoperatorfactory/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IMathNaryOperatorFactory](../../com.aspose.slides/imathnaryoperatorfactory)
```
public class MathNaryOperatorFactory implements IMathNaryOperatorFactory
```

IMathNaryOperator를 만들 수 있습니다

--------------------

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MathNaryOperatorFactory()](#MathNaryOperatorFactory--) |  |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | IMathNaryOperator를 생성합니다 |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | IMathNaryOperator를 생성합니다 |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | IMathNaryOperator를 생성합니다 |

### MathNaryOperatorFactory() {#MathNaryOperatorFactory--}
```
public MathNaryOperatorFactory()
```

### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
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
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 새 IMathNaryOperator

### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

IMathNaryOperator를 생성합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| operatorSymbol | char | 연산자 기호 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 연산자를 적용할 기본 인수 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 하한 |

**반환값:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 새 IMathNaryOperator

### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

IMathNaryOperator를 생성합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| operatorSymbol | char | 연산자 기호 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 연산자를 적용할 기본 인수 |

**반환값:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 새 IMathNaryOperator