---
title: Integral()
second_title: Aspose.Slides för C++ API-referens
description: Tar integralen
type: docs
weight: 183
url: /sv/aspose.slides.mathtext/mathelementbase/integral/
---
## MathElementBase::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathLimitLocations) metod


Tar integralen

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit, MathLimitLocations limitLocations) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integral type |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Lower limit of integral |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Upper limit of integral |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | location of limits |

### Returvärde

Ny instans av typ [IMathNaryOperator](../../imathnaryoperator/)
## Anmärkningar



Exempel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metod


Tar integralen

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integral type |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Lower limit of integral |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Upper limit of integral |

### Returvärde

Ny instans av typ [IMathNaryOperator](../../imathnaryoperator/)
## Anmärkningar



Exempel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"?\?");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes) metod


Tar integralen utan gränser

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integral type |

### Returvärde

Ny instans av typ [IMathNaryOperator](../../imathnaryoperator/)
## Anmärkningar



Exempel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Contour);
```

## MathElementBase::Integral(MathIntegralTypes, System::String, System::String, MathLimitLocations) metod


Tar integralen

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit, MathLimitLocations limitLocations) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integral type |
| lowerLimit | [System::String](../../../system/string/) | Lower limit of integral |
| upperLimit | [System::String](../../../system/string/) | Upper limit of integral |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | location of limits |

### Returvärde

Ny instans av typ [IMathNaryOperator](../../imathnaryoperator/)
## Anmärkningar



Exempel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5", MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes, System::String, System::String) metod


Tar integralen

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integral type |
| lowerLimit | [System::String](../../../system/string/) | Lower limit of integral |
| upperLimit | [System::String](../../../system/string/) | Upper limit of integral |

### Returvärde

Ny instans av typ [IMathNaryOperator](../../imathnaryoperator/)
## Anmärkningar



Exempel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5");
```

## Se också

* Enum [MathIntegralTypes](../../mathintegraltypes/)
* Enum [MathLimitLocations](../../mathlimitlocations/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathNaryOperator](../../imathnaryoperator/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)