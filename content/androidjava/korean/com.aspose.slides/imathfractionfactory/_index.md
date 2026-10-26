---
title: IMathFractionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math fraction
type: docs
url: /ko/com.aspose.slides/imathfractionfactory/
---```
public interface IMathFractionFactory
```

수학 분수를 생성할 수 있습니다

--------------------

COM 호환성을 위해
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | 수학 분수를 생성합니다 |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 수학 분수를 생성합니다 |
### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


수학 분수를 생성합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | 분자 |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 분모 |
| fractionType | int | 분수 유형 |

**반환값:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 새 수학 분수 [IMathFraction](../../com.aspose.slides/imathfraction)
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```


수학 분수를 생성합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | 분자 |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 분모 |

**반환값:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 새 수학 분수 [IMathFraction](../../com.aspose.slides/imathfraction)