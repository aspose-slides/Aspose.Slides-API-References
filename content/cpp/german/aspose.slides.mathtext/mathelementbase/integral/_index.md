---
title: Integral()
second_title: Aspose.Slides für C++ API-Referenz
description: Nimmt das Integral
type: docs
weight: 183
url: /de/aspose.slides.mathtext/mathelementbase/integral/
---
## MathElementBase::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathLimitLocations) method

Nimmt das Integral

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit, MathLimitLocations limitLocations) override
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integraltyp |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Untere Grenze des Integrals |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Obere Grenze des Integrals |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | Position der Grenzen |

### Rückgabewert

Neue Instanz des Typs [IMathNaryOperator](../../imathnaryoperator/)

## Bemerkungen



Beispiel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method

Nimmt das Integral

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit) override
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integraltyp |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Untere Grenze des Integrals |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Obere Grenze des Integrals |

### Rückgabewert

Neue Instanz des Typs [IMathNaryOperator](../../imathnaryoperator/)

## Bemerkungen



Beispiel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"?\?");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes) method

Nimmt das Integral ohne Grenzen

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType) override
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integraltyp |

### Rückgabewert

Neue Instanz des Typs [IMathNaryOperator](../../imathnaryoperator/)

## Bemerkungen



Beispiel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Contour);
```

## MathElementBase::Integral(MathIntegralTypes, System::String, System::String, MathLimitLocations) method

Nimmt das Integral

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit, MathLimitLocations limitLocations) override
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integraltyp |
| lowerLimit | [System::String](../../../system/string/) | Untere Grenze des Integrals |
| upperLimit | [System::String](../../../system/string/) | Obere Grenze des Integrals |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | Position der Grenzen |

### Rückgabewert

Neue Instanz des Typs [IMathNaryOperator](../../imathnaryoperator/)

## Bemerkungen



Beispiel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5", MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes, System::String, System::String) method

Nimmt das Integral

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit) override
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integraltyp |
| lowerLimit | [System::String](../../../system/string/) | Untere Grenze des Integrals |
| upperLimit | [System::String](../../../system/string/) | Obere Grenze des Integrals |

### Rückgabewert

Neue Instanz des Typs [IMathNaryOperator](../../imathnaryoperator/)

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
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathElementBase](../)
* Klasse [String](../../../system/string/)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)