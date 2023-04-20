---
title: Integral()
second_title: Aspose.Slides for C++ API Reference
description: Takes the integral
type: docs
weight: 183
url: /cpp/aspose.slides.mathtext/mathelementbase/integral/
---
## MathElementBase::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathLimitLocations) method


Takes the integral

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit, MathLimitLocations limitLocations) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integral type |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Lower limit of integral |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Upper limit of integral |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | location of limits |

### Return Value

New instance of type [IMathNaryOperator](../../imathnaryoperator/)
## Remarks



Example: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(Aspose::Slides::MathText::MathIntegralTypes::Simple, lowerLimit, upperLimit, Aspose::Slides::MathText::MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method


Takes the integral

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integral type |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Lower limit of integral |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Upper limit of integral |

### Return Value

New instance of type [IMathNaryOperator](../../imathnaryoperator/)
## Remarks



Example: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"?\?");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes) method


Takes the integral without limits

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integral type |

### Return Value

New instance of type [IMathNaryOperator](../../imathnaryoperator/)
## Remarks



Example: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(Aspose::Slides::MathText::MathIntegralTypes::Contour);
```

## MathElementBase::Integral(MathIntegralTypes, System::String, System::String, MathLimitLocations) method


Takes the integral

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit, MathLimitLocations limitLocations) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integral type |
| lowerLimit | [System::String](../../../system/string/) | Lower limit of integral |
| upperLimit | [System::String](../../../system/string/) | Upper limit of integral |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | location of limits |

### Return Value

New instance of type [IMathNaryOperator](../../imathnaryoperator/)
## Remarks



Example: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(Aspose::Slides::MathText::MathIntegralTypes::Simple, u"1", u"5", Aspose::Slides::MathText::MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes, System::String, System::String) method


Takes the integral

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integral type |
| lowerLimit | [System::String](../../../system/string/) | Lower limit of integral |
| upperLimit | [System::String](../../../system/string/) | Upper limit of integral |

### Return Value

New instance of type [IMathNaryOperator](../../imathnaryoperator/)
## Remarks



Example: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(Aspose::Slides::MathText::MathIntegralTypes::Simple, u"1", u"5");
```

## See Also

* Enum [MathIntegralTypes](../../mathintegraltypes/)
* Enum [MathLimitLocations](../../mathlimitlocations/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathNaryOperator](../../imathnaryoperator/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)