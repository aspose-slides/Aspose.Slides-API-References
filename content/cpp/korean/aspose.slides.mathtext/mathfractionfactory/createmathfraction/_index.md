---
title: CreateMathFraction()
second_title: Aspose.Slides for C++ API 참조
description: 수학 분수를 생성합니다
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/mathfractionfactory/createmathfraction/
---
## MathFractionFactory::CreateMathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathFractionTypes) 메서드

수학 분수를 생성합니다

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathFractionFactory::CreateMathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 분자 |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 분모 |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | 분수 유형 |

### 반환값



## MathFractionFactory::CreateMathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) 메서드

수학 분수를 생성합니다

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathFractionFactory::CreateMathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 분자 |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 분모 |

### 반환값



## 참고

* 열거형 [MathFractionTypes](../../mathfractiontypes/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathFraction](../../imathfraction/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathFractionFactory](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)