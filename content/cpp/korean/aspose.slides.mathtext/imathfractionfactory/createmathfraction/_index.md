---
title: CreateMathFraction()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 수학 분수를 생성합니다
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/imathfractionfactory/createmathfraction/
---
## IMathFractionFactory::CreateMathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathFractionTypes) 메서드

수학 분수를 생성합니다

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathFractionFactory::CreateMathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 분자 |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 분모 |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | 분수 유형 |

### 반환 값

새로운 수학 분수 [IMathFraction](../../imathfraction/)

## IMathFractionFactory::CreateMathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) 메서드

수학 분수를 생성합니다

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathFractionFactory::CreateMathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 분자 |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 분모 |

### 반환 값

새로운 수학 분수 [IMathFraction](../../imathfraction/)

## 참고

* 열거형 [MathFractionTypes](../../mathfractiontypes/)
* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathFraction](../../imathfraction/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [IMathFractionFactory](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)