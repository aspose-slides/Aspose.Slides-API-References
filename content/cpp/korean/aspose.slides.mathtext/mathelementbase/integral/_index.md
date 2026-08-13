---
title: Integral()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 적분을 수행합니다
type: docs
weight: 183
url: /ko/aspose.slides.mathtext/mathelementbase/integral/
---
## MathElementBase::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathLimitLocations) 메서드


적분을 수행합니다

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit, MathLimitLocations limitLocations) override
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | 적분 유형 |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 적분의 하한 |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 적분의 상한 |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | 한계점 위치 |

### 반환 값

새 인스턴스 유형 [IMathNaryOperator](../../imathnaryoperator/)
## 비고



예제: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) 메서드


적분을 수행합니다

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit) override
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | 적분 유형 |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 적분의 하한 |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 적분의 상한 |

### 반환 값

새 인스턴스 유형 [IMathNaryOperator](../../imathnaryoperator/)
## 비고



예제: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"?\?");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes) 메서드


적분을 수행합니다 (제한 없이)

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType) override
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | 적분 유형 |

### 반환 값

새 인스턴스 유형 [IMathNaryOperator](../../imathnaryoperator/)
## 비고



예제: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Contour);
```

## MathElementBase::Integral(MathIntegralTypes, System::String, System::String, MathLimitLocations) 메서드


적분을 수행합니다

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit, MathLimitLocations limitLocations) override
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | 적분 유형 |
| lowerLimit | [System::String](../../../system/string/) | 적분의 하한 |
| upperLimit | [System::String](../../../system/string/) | 적분의 상한 |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | 한계점 위치 |

### 반환 값

새 인스턴스 유형 [IMathNaryOperator](../../imathnaryoperator/)
## 비고



예제: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5", MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes, System::String, System::String) 메서드


적분을 수행합니다

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit) override
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | 적분 유형 |
| lowerLimit | [System::String](../../../system/string/) | 적분의 하한 |
| upperLimit | [System::String](../../../system/string/) | 적분의 상한 |

### 반환 값

새 인스턴스 유형 [IMathNaryOperator](../../imathnaryoperator/)
## 비고



예제: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5");
```

## See Also

* Enum [MathIntegralTypes](../../mathintegraltypes/)
* Enum [MathLimitLocations](../../mathlimitlocations/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathNaryOperator](../../imathnaryoperator/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)