---
title: Integral()
second_title: Aspose.Slides für C++ API-Referenz
description: Nimmt das Integral
type: docs
weight: 196
url: /de/aspose.slides.mathtext/imathelement/integral/
---
## IMathElement::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathLimitLocations) method

Nimmt das Integral

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit, MathLimitLocations limitLocations)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integraltyp |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Untere Grenze des Integrals |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Obere Grenze des Integrals |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | Ort der Grenzen |

### Rückgabewert

Neue Instanz vom Typ [IMathNaryOperator](../../imathnaryoperator/)
## Bemerkungen

Beispiel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method

Nimmt das Integral

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integraltyp |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Untere Grenze des Integrals |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Obere Grenze des Integrals |

### Rückgabewert

Neue Instanz vom Typ [IMathNaryOperator](../../imathnaryoperator/)
## Bemerkungen

Beispiel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes) method

Nimmt das Integral ohne Grenzen

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integraltyp |

### Rückgabewert

Neue Instanz vom Typ [IMathNaryOperator](../../imathnaryoperator/)
## Bemerkungen

Beispiel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Contour);
```

## IMathElement::Integral(MathIntegralTypes, System::String, System::String, MathLimitLocations) method

Nimmt das Integral

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit, MathLimitLocations limitLocations)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integraltyp |
| lowerLimit | [System::String](../../../system/string/) | Untere Grenze des Integrals |
| upperLimit | [System::String](../../../system/string/) | Obere Grenze des Integrals |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | Ort der Grenzen |

### Rückgabewert

Neue Instanz vom Typ [IMathNaryOperator](../../imathnaryoperator/)
## Bemerkungen

Beispiel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5", MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes, System::String, System::String) method

Nimmt das Integral

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integraltyp |
| lowerLimit | [System::String](../../../system/string/) | Untere Grenze des Integrals |
| upperLimit | [System::String](../../../system/string/) | Obere Grenze des Integrals |

### Rückgabewert

Neue Instanz vom Typ [IMathNaryOperator](../../imathnaryoperator/)
## Bemerkungen

Beispiel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5");
```

## Siehe auch

* Enum [MathIntegralTypes](../../mathintegraltypes/)
* Enum [MathLimitLocations](../../mathlimitlocations/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathNaryOperator](../../imathnaryoperator/)
* Klasse [IMathElement](../)
* Klasse [String](../../../system/string/)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)