---
title: Integral()
second_title: Aspose.Slides C++ API referencia
description: Elvégzi az integrálást
type: docs
weight: 196
url: /hu/aspose.slides.mathtext/imathelement/integral/
---
## IMathElement::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathLimitLocations) method


Elvégzi az integrálást

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit, MathLimitLocations limitLocations)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integrál típusa |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Integrál alsó határa |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Integrál felső határa |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | a határok helye |

### Visszatérési érték

Új példány a [IMathNaryOperator](../../imathnaryoperator/) típusból
## Megjegyzés



Példa: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method


Elvégzi az integrálást

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integrál típusa |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Integrál alsó határa |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Integrál felső határa |

### Visszatérési érték

Új példány a [IMathNaryOperator](../../imathnaryoperator/) típusból
## Megjegyzés



Példa: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes) method


Az integrált korlátok nélkül végzi el

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integrál típusa |

### Visszatérési érték

Új példány a [IMathNaryOperator](../../imathnaryoperator/) típusból
## Megjegyzés



Példa: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Contour);
```

## IMathElement::Integral(MathIntegralTypes, System::String, System::String, MathLimitLocations) method


Elvégzi az integrálást

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit, MathLimitLocations limitLocations)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integrál típusa |
| lowerLimit | [System::String](../../../system/string/) | Integrál alsó határa |
| upperLimit | [System::String](../../../system/string/) | Integrál felső határa |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | a határok helye |

### Visszatérési érték

Új példány a [IMathNaryOperator](../../imathnaryoperator/) típusból
## Megjegyzés



Példa: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5", MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes, System::String, System::String) method


Elvégzi az integrálást

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integrál típusa |
| lowerLimit | [System::String](../../../system/string/) | Integrál alsó határa |
| upperLimit | [System::String](../../../system/string/) | Integrál felső határa |

### Visszatérési érték

Új példány a [IMathNaryOperator](../../imathnaryoperator/) típusból
## Megjegyzés



Példa: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5");
```

## Lásd még

* Enum [MathIntegralTypes](../../mathintegraltypes/)
* Enum [MathLimitLocations](../../mathlimitlocations/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathNaryOperator](../../imathnaryoperator/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)