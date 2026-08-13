---
title: Integral()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 적분을 수행합니다
type: docs
weight: 196
url: /ko/aspose.slides.mathtext/imathelement/integral/
---
## IMathElement::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathLimitLocations) 메서드


적분을 취합니다

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit, MathLimitLocations limitLocations)=0
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | 적분 유형 |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 적분의 하한 |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 적분의 상한 |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | 제한 위치 |

### 반환값

새 인스턴스 유형 [IMathNaryOperator](../../imathnaryoperator/)
## 비고



예시: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) 메서드


적분을 취합니다

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)=0
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | 적분 유형 |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 적분의 하한 |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 적분의 상한 |

### 반환값

새 인스턴스 유형 [IMathNaryOperator](../../imathnaryoperator/)
## 비고



예시: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes) 메서드


제한 없이 적분을 취합니다

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType)=0
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | 적분 유형 |

### 반환값

새 인스턴스 유형 [IMathNaryOperator](../../imathnaryoperator/)
## 비고



예시: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Contour);
```

## IMathElement::Integral(MathIntegralTypes, System::String, System::String, MathLimitLocations) 메서드


적분을 취합니다

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit, MathLimitLocations limitLocations)=0
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | 적분 유형 |
| lowerLimit | [System::String](../../../system/string/) | 적분의 하한 |
| upperLimit | [System::String](../../../system/string/) | 적분의 상한 |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | 제한 위치 |

### 반환값

새 인스턴스 유형 [IMathNaryOperator](../../imathnaryoperator/)
## 비고



예시: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5", MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes, System::String, System::String) 메서드


적분을 취합니다

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit)=0
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | 적분 유형 |
| lowerLimit | [System::String](../../../system/string/) | 적분의 하한 |
| upperLimit | [System::String](../../../system/string/) | 적분의 상한 |

### 반환값

새 인스턴스 유형 [IMathNaryOperator](../../imathnaryoperator/)
## 비고



예시: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5");
```

## 참고

* Enum [MathIntegralTypes](../../mathintegraltypes/)
* Enum [MathLimitLocations](../../mathlimitlocations/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathNaryOperator](../../imathnaryoperator/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)