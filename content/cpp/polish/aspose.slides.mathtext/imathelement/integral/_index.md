---
title: Integral()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Oblicza całkę
type: docs
weight: 196
url: /pl/aspose.slides.mathtext/imathelement/integral/
---
## IMathElement::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathLimitLocations) metoda


Oblicza całkę

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit, MathLimitLocations limitLocations)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Typ całki |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Dolny limit całki |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Górny limit całki |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | położenie limitów |

### Wartość zwracana

Nowa instancja typu [IMathNaryOperator](../../imathnaryoperator/)
## Uwaga



Przykład: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metoda


Oblicza całkę

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Typ całki |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Dolny limit całki |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Górny limit całki |

### Wartość zwracana

Nowa instancja typu [IMathNaryOperator](../../imathnaryoperator/)
## Uwaga



Przykład: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes) metoda


Oblicza całkę bez limitów

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Typ całki |

### Wartość zwracana

Nowa instancja typu [IMathNaryOperator](../../imathnaryoperator/)
## Uwaga



Przykład: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Contour);
```

## IMathElement::Integral(MathIntegralTypes, System::String, System::String, MathLimitLocations) metoda


Oblicza całkę

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit, MathLimitLocations limitLocations)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Typ całki |
| lowerLimit | [System::String](../../../system/string/) | Dolny limit całki |
| upperLimit | [System::String](../../../system/string/) | Górny limit całki |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | położenie limitów |

### Wartość zwracana

Nowa instancja typu [IMathNaryOperator](../../imathnaryoperator/)
## Uwaga



Przykład: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5", MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes, System::String, System::String) metoda


Oblicza całkę

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Typ całki |
| lowerLimit | [System::String](../../../system/string/) | Dolny limit całki |
| upperLimit | [System::String](../../../system/string/) | Górny limit całki |

### Wartość zwracana

Nowa instancja typu [IMathNaryOperator](../../imathnaryoperator/)
## Uwaga



Przykład: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5");
```

## Zobacz także

* Enum [MathIntegralTypes](../../mathintegraltypes/)
* Enum [MathLimitLocations](../../mathlimitlocations/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathNaryOperator](../../imathnaryoperator/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)