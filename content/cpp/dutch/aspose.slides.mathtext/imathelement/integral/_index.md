---
title: Integral()
second_title: Aspose.Slides voor C++ API-referentie
description: Voert de integraal uit
type: docs
weight: 196
url: /nl/aspose.slides.mathtext/imathelement/integral/
---
## IMathElement::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathLimitLocations) methode

Voert de integraal uit

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit, MathLimitLocations limitLocations)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integratietype |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Ondergrens van integraal |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Bovengrens van integraal |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | locatie van grenzen |

### Retourwaarde

New instance of type [IMathNaryOperator](../../imathnaryoperator/)
## Opmerkingen



Voorbeeld: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) methode


Voert de integraal uit

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integratietype |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Ondergrens van integraal |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Bovengrens van integraal |

### Retourwaarde

New instance of type [IMathNaryOperator](../../imathnaryoperator/)
## Opmerkingen



Voorbeeld: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes) methode


Voert de integraal uit zonder grenzen

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integratietype |

### Retourwaarde

New instance of type [IMathNaryOperator](../../imathnaryoperator/)
## Opmerkingen



Voorbeeld: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Contour);
```

## IMathElement::Integral(MathIntegralTypes, System::String, System::String, MathLimitLocations) methode


Voert de integraal uit

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit, MathLimitLocations limitLocations)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integratietype |
| lowerLimit | [System::String](../../../system/string/) | Ondergrens van integraal |
| upperLimit | [System::String](../../../system/string/) | Bovengrens van integraal |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | locatie van grenzen |

### Retourwaarde

New instance of type [IMathNaryOperator](../../imathnaryoperator/)
## Opmerkingen



Voorbeeld: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5", MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes, System::String, System::String) methode


Voert de integraal uit

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integratietype |
| lowerLimit | [System::String](../../../system/string/) | Ondergrens van integraal |
| upperLimit | [System::String](../../../system/string/) | Bovengrens van integraal |

### Retourwaarde

New instance of type [IMathNaryOperator](../../imathnaryoperator/)
## Opmerkingen



Voorbeeld: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5");
```

## Zie ook

* Enum [MathIntegralTypes](../../mathintegraltypes/)
* Enum [MathLimitLocations](../../mathlimitlocations/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathNaryOperator](../../imathnaryoperator/)
* Klasse [IMathElement](../)
* Klasse [String](../../../system/string/)
* Naamruimte [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)