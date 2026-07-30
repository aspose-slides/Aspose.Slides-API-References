---
title: Integral()
second_title: Aspose.Slides pro referenci API C++
description: Přijímá integrál
type: docs
weight: 183
url: /cs/aspose.slides.mathtext/mathelementbase/integral/
---
## MathElementBase::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathLimitLocations) metoda


Přijímá integrál

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit, MathLimitLocations limitLocations) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Typ integrálu |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Dolní mez integrálu |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Horní mez integrálu |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | umístění limitů |

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

## MathElementBase::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metoda


Přijímá integrál

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Typ integrálu |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Dolní mez integrálu |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Horní mez integrálu |

### Návratová hodnota

Nová instance typu [IMathNaryOperator](../../imathnaryoperator/)
## Poznámky



Příklad: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"?\?");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes) metoda


Přijímá integrál bez limitů

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType) override
```


### Argumenty

| Parametr | Typ | Popis |
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

## MathElementBase::Integral(MathIntegralTypes, System::String, System::String, MathLimitLocations) metoda


Přijímá integrál

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit, MathLimitLocations limitLocations) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Typ integrálu |
| lowerLimit | [System::String](../../../system/string/) | Dolní mez integrálu |
| upperLimit | [System::String](../../../system/string/) | Horní mez integrálu |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | umístění limitů |

### Návratová hodnota

Nová instance typu [IMathNaryOperator](../../imathnaryoperator/)
## Poznámky



Příklad: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5", MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes, System::String, System::String) metoda


Přijímá integrál

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit) override
```


### Argumenty

| Parametr | Typ | Popis |
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

* Enum [MathIntegralTypes](../../mathintegraltypes/)
* Enum [MathLimitLocations](../../mathlimitlocations/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathNaryOperator](../../imathnaryoperator/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)