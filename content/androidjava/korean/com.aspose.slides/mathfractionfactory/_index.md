---
title: MathFractionFactory
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 수학 분수를 만들 수 있습니다
type: docs
url: /ko/com.aspose.slides/mathfractionfactory/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IMathFractionFactory](../../com.aspose.slides/imathfractionfactory)
```
public class MathFractionFactory implements IMathFractionFactory
```

수학 분수를 만들 수 있습니다

--------------------

COM 호환성을 위해
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MathFractionFactory()](#MathFractionFactory--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | 수학 분수를 생성합니다 |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 수학 분수를 생성합니다 |
### MathFractionFactory() {#MathFractionFactory--}
```
public MathFractionFactory()
```


### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


수학 분수를 생성합니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | 분자 |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 분모 |
| fractionType | int | 분수 유형 |

**반환값:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 새 수학 분수
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```


수학 분수를 생성합니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | 분자 |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 분모 |

**반환값:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 새 수학 분수