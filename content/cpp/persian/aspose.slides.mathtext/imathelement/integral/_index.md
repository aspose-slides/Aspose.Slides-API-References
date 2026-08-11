---
title: Integral()
second_title: مرجع API Aspose.Slides برای C++
description: انتگرال را می‌گیرد
type: docs
weight: 196
url: /fa/aspose.slides.mathtext/imathelement/integral/
---
## IMathElement::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathLimitLocations) متد

انتگرال را می‌گیرد

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit, MathLimitLocations limitLocations)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integral type |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Lower limit of integral |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Upper limit of integral |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | location of limits |

### مقدار برگشتی

نمونه جدید از نوع [IMathNaryOperator](../../imathnaryoperator/)
## نکات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) متد

انتگرال را می‌گیرد

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integral type |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Lower limit of integral |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Upper limit of integral |

### مقدار برگشتی

نمونه جدید از نوع [IMathNaryOperator](../../imathnaryoperator/)
## نکات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes) متد

انتگرال را بدون حدود می‌گیرد

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integral type |

### مقدار برگشتی

نمونه جدید از نوع [IMathNaryOperator](../../imathnaryoperator/)
## نکات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Contour);
```

## IMathElement::Integral(MathIntegralTypes, System::String, System::String, MathLimitLocations) متد

انتگرال را می‌گیرد

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit, MathLimitLocations limitLocations)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integral type |
| lowerLimit | [System::String](../../../system/string/) | Lower limit of integral |
| upperLimit | [System::String](../../../system/string/) | Upper limit of integral |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | location of limits |

### مقدار برگشتی

نمونه جدید از نوع [IMathNaryOperator](../../imathnaryoperator/)
## نکات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5", MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes, System::String, System::String) متد

انتگرال را می‌گیرد

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integral type |
| lowerLimit | [System::String](../../../system/string/) | Lower limit of integral |
| upperLimit | [System::String](../../../system/string/) | Upper limit of integral |

### مقدار برگشتی

نمونه جدید از نوع [IMathNaryOperator](../../imathnaryoperator/)
## نکات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5");
```

## همچنین ببینید

* enum [MathIntegralTypes](../../mathintegraltypes/)
* enum [MathLimitLocations](../../mathlimitlocations/)
* typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathNaryOperator](../../imathnaryoperator/)
* کلاس [IMathElement](../)
* کلاس [String](../../../system/string/)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)