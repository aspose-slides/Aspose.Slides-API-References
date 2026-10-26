---
title: Integral()
second_title: Aspose.Slides لـ C++ مرجع API
description: يأخذ التكامل
type: docs
weight: 196
url: /ar/aspose.slides.mathtext/imathelement/integral/
---
## IMathElement::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathLimitLocations) طريقة

يأخذ التكامل

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit, MathLimitLocations limitLocations)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integral type |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Lower limit of integral |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Upper limit of integral |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | location of limits |

### قيمة الإرجاع

مثيل جديد من النوع [IMathNaryOperator](../../imathnaryoperator/)
## ملاحظات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) طريقة


يأخذ التكامل

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integral type |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Lower limit of integral |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Upper limit of integral |

### قيمة الإرجاع

مثيل جديد من النوع [IMathNaryOperator](../../imathnaryoperator/)
## ملاحظات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes) طريقة


يأخذ التكامل بدون حدود

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integral type |

### قيمة الإرجاع

مثيل جديد من النوع [IMathNaryOperator](../../imathnaryoperator/)
## ملاحظات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Contour);
```

## IMathElement::Integral(MathIntegralTypes, System::String, System::String, MathLimitLocations) طريقة


يأخذ التكامل

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit, MathLimitLocations limitLocations)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integral type |
| lowerLimit | [System::String](../../../system/string/) | Lower limit of integral |
| upperLimit | [System::String](../../../system/string/) | Upper limit of integral |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | location of limits |

### قيمة الإرجاع

مثيل جديد من النوع [IMathNaryOperator](../../imathnaryoperator/)
## ملاحظات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5", MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes, System::String, System::String) طريقة


يأخذ التكامل

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integral type |
| lowerLimit | [System::String](../../../system/string/) | Lower limit of integral |
| upperLimit | [System::String](../../../system/string/) | Upper limit of integral |

### قيمة الإرجاع

مثيل جديد من النوع [IMathNaryOperator](../../imathnaryoperator/)
## ملاحظات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5");
```

## انظر أيضًا

* Enum [MathIntegralTypes](../../mathintegraltypes/)
* Enum [MathLimitLocations](../../mathlimitlocations/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathNaryOperator](../../imathnaryoperator/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)