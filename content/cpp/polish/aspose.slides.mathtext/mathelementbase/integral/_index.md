---
title: Integral()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Pobiera całkę
type: docs
weight: 183
url: /pl/aspose.slides.mathtext/mathelementbase/integral/
---
## MathElementBase::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathLimitLocations) metoda


Pobiera całkę

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit, MathLimitLocations limitLocations) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Typ całki |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Dolna granica całki |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Górna granica całki |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | Lokalizacja limitów |

### Wartość zwracana

Nowa instancja typu [IMathNaryOperator](../../imathnaryoperator/)
## Uwagi



Przykład: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metoda


Pobiera całkę

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Typ całki |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Dolna granica całki |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Górna granica całki |

### Wartość zwracana

Nowa instancja typu [IMathNaryOperator](../../imathnaryoperator/)
## Uwagi



Przykład: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"?\?");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes) metoda


Pobiera całkę bez limitów

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Typ całki |

### Wartość zwracana

Nowa instancja typu [IMathNaryOperator](../../imathnaryoperator/)
## Uwagi



Przykład: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Contour);
```

## MathElementBase::Integral(MathIntegralTypes, System::String, System::String, MathLimitLocations) metoda


Pobiera całkę

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit, MathLimitLocations limitLocations) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Typ całki |
| lowerLimit | [System::String](../../../system/string/) | Dolna granica całki |
| upperLimit | [System::String](../../../system/string/) | Górna granica całki |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | Lokalizacja limitów |

### Wartość zwracana

Nowa instancja typu [IMathNaryOperator](../../imathnaryoperator/)
## Uwagi



Przykład: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5", MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes, System::String, System::String) metoda


Pobiera całkę

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Typ całki |
| lowerLimit | [System::String](../../../system/string/) | Dolna granica całki |
| upperLimit | [System::String](../../../system/string/) | Górna granica całki |

### Wartość zwracana

Nowa instancja typu [IMathNaryOperator](../../imathnaryoperator/)
## Uwagi



Przykład: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5");
```

## Zobacz także

* Enum [MathIntegralTypes](../../mathintegraltypes/)
* Enum [MathLimitLocations](../../mathlimitlocations/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathNaryOperator](../../imathnaryoperator/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathElementBase](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)