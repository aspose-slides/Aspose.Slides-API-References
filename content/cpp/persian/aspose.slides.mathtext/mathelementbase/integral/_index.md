---
title: Integral()
second_title: مرجع API برای Aspose.Slides برای C++
description: یک انتگرال می‌گیرد
type: docs
weight: 183
url: /fa/aspose.slides.mathtext/mathelementbase/integral/
---
## MathElementBase::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathLimitLocations) متد

یک انتگرال می‌گیرد

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit, MathLimitLocations limitLocations) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | نوع انتگرال |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | حد پایین انتگرال |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | حد بالای انتگرال |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | موقعیت حدود |

### مقدار بازگشت

نمونه جدید از نوع [IMathNaryOperator](../../imathnaryoperator/)
## توضیحات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) متد

یک انتگرال می‌گیرد

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | نوع انتگرال |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | حد پایین انتگرال |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | حد بالای انتگرال |

### مقدار بازگشت

نمونه جدید از نوع [IMathNaryOperator](../../imathnaryoperator/)
## توضیحات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"?\?");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes) متد

یک انتگرال را بدون حدود می‌گیرد

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | نوع انتگرال |

### مقدار بازگشت

نمونه جدید از نوع [IMathNaryOperator](../../imathnaryoperator/)
## توضیحات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Contour);
```

## MathElementBase::Integral(MathIntegralTypes, System::String, System::String, MathLimitLocations) متد

یک انتگرال می‌گیرد

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit, MathLimitLocations limitLocations) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | نوع انتگرال |
| lowerLimit | [System::String](../../../system/string/) | حد پایین انتگرال |
| upperLimit | [System::String](../../../system/string/) | حد بالای انتگرال |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | موقعیت حدود |

### مقدار بازگشت

نمونه جدید از نوع [IMathNaryOperator](../../imathnaryoperator/)
## توضیحات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5", MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes, System::String, System::String) متد

یک انتگرال می‌گیرد

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | نوع انتگرال |
| lowerLimit | [System::String](../../../system/string/) | حد پایین انتگرال |
| upperLimit | [System::String](../../../system/string/) | حد بالای انتگرال |

### مقدار بازگشت

نمونه جدید از نوع [IMathNaryOperator](../../imathnaryoperator/)
## توضیحات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5");
```

## موارد مرتبط

* Enum [MathIntegralTypes](../../mathintegraltypes/)
* Enum [MathLimitLocations](../../mathlimitlocations/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathNaryOperator](../../imathnaryoperator/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathElementBase](../)
* کلاس [String](../../../system/string/)
* فضای‌نام [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)