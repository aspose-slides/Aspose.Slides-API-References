---
title: Divide()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 분자와 지정된 분모를 사용하여 분수를 생성합니다
type: docs
weight: 27
url: /ko/aspose.slides.mathtext/imathelement/divide/
---
## IMathElement::Divide(System::SharedPtr\<IMathElement\>) 메서드

이 분자와 지정된 분모를 사용하여 분수를 생성합니다

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 분모 |

### 반환 값

새 분수
## 비고



예: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## IMathElement::Divide(System::String) 메서드

이 분자와 지정된 분모를 사용하여 분수를 생성합니다

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | 분모 |

### 반환 값

새 분수
## 비고



예: 
```cpp
System::SharedPtr<IMathElement> numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## IMathElement::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) 메서드

이 분자와 지정된 분모를 사용하여 지정된 유형의 분수를 생성합니다

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 분모 |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | 분수 유형: Bar, NoBar, Skewed, Linear |

### 반환 값

새 분수
## 비고



예: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator, MathFractionTypes::Linear);
```

## IMathElement::Divide(System::String, MathFractionTypes) 메서드

이 분자와 지정된 분모를 사용하여 지정된 유형의 분수를 생성합니다

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator, MathFractionTypes fractionType)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | 분모 |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | 분수 유형: Bar, NoBar, Skewed, Linear |

### 반환 값

새 분수
## 비고



예: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y", MathFractionTypes::Linear);
```

## 참조

* 열거형 [MathFractionTypes](../../mathfractiontypes/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathFraction](../../imathfraction/)
* 클래스 [IMathElement](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)