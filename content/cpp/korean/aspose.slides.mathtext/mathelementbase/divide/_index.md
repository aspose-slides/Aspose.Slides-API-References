---
title: Divide()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 분자와 지정된 분모로 분수를 생성합니다
type: docs
weight: 14
url: /ko/aspose.slides.mathtext/mathelementbase/divide/
---
## MathElementBase::Divide(System::SharedPtr\<IMathElement\>) 메서드

이 분자와 지정된 분모로 분수를 생성합니다

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 분모 |

### 반환 값

새 분수
## 비고



예: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## MathElementBase::Divide(System::String) 메서드

이 분자와 지정된 분모로 분수를 생성합니다

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator) override
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
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## MathElementBase::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) 메서드

이 분자와 지정된 분모로 지정된 유형의 분수를 생성합니다

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 분모 |
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

## MathElementBase::Divide(System::String, MathFractionTypes) 메서드

이 분자와 지정된 분모로 지정된 유형의 분수를 생성합니다

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator, MathFractionTypes fractionType) override
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

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFraction](../../imathfraction/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)