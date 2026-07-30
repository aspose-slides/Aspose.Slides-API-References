---
title: Integral()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Provádí integrál
type: docs
weight: 196
url: /cs/aspose.slides.mathtext/imathelement/integral/
---
## IMathElement::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathLimitLocations) metoda


Provádí integrál

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit, MathLimitLocations limitLocations)=0
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Typ integrálu |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Dolní mez integrálu |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Horní mez integrálu |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | umístění mezí |

### Návratová hodnota

Nová instance typu [IMathNaryOperator](../../imathnaryoperator/)
## Poznámky



Příklad: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metoda


Provádí integrál

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)=0
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Typ integrálu |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Dolní mez integrálu |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Horní mez integrálu |

### Návratová hodnota

Nová instance typu [IMathNaryOperator](../../imathnaryoperator/)
## Poznámky



Příklad: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes) metoda


Provádí integrál bez mezí

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType)=0
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Typ integrálu |

### Návratová hodnota

Nová instance typu [IMathNaryOperator](../../imathnaryoperator/)
## Poznámky



Příklad: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Contour);
```

## IMathElement::Integral(MathIntegralTypes, System::String, System::String, MathLimitLocations) metoda


Provádí integrál

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit, MathLimitLocations limitLocations)=0
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Typ integrálu |
| lowerLimit | [System::String](../../../system/string/) | Dolní mez integrálu |
| upperLimit | [System::String](../../../system/string/) | Horní mez integrálu |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | umístění mezí |

### Návratová hodnota

Nová instance typu [IMathNaryOperator](../../imathnaryoperator/)
## Poznámky



Příklad: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5", MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes, System::String, System::String) metoda


Provádí integrál

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit)=0
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Typ integrálu |
| lowerLimit | [System::String](../../../system/string/) | Dolní mez integrálu |
| upperLimit | [System::String](../../../system/string/) | Horní mez integrálu |

### Návratová hodnota

Nová instance typu [IMathNaryOperator](../../imathnaryoperator/)
## Poznámky



Příklad: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5");
```

## Viz také

* Výčtový typ [MathIntegralTypes](../../mathintegraltypes/)
* Výčtový typ [MathLimitLocations](../../mathlimitlocations/)
* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [IMathNaryOperator](../../imathnaryoperator/)
* Třída [IMathElement](../)
* Třída [String](../../../system/string/)
* Prostor názvů [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)