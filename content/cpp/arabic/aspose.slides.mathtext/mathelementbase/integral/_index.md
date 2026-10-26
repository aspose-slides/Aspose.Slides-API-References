---
title: Integral()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يأخذ التكامل
type: docs
weight: 183
url: /ar/aspose.slides.mathtext/mathelementbase/integral/
---
## MathElementBase::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathLimitLocations) طريقة

يأخذ التكامل

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit, MathLimitLocations limitLocations) override
```

### المعلمات
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | نوع التكامل |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | الحد الأدنى للتكامل |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | الحد الأعلى للتكامل |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | موقع الحدود |

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

## MathElementBase::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) طريقة

يأخذ التكامل

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit) override
```

### المعلمات
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | نوع التكامل |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | الحد الأدنى للتكامل |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | الحد الأعلى للتكامل |

### قيمة الإرجاع
مثيل جديد من النوع [IMathNaryOperator](../../imathnaryoperator/)

## ملاحظات



مثال:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"?\?");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes) طريقة

يأخذ التكامل بدون حدود

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType) override
```

### المعلمات
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | نوع التكامل |

### قيمة الإرجاع
مثيل جديد من النوع [IMathNaryOperator](../../imathnaryoperator/)

## ملاحظات



مثال:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Contour);
```

## MathElementBase::Integral(MathIntegralTypes, System::String, System::String, MathLimitLocations) طريقة

يأخذ التكامل

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit, MathLimitLocations limitLocations) override
```

### المعلمات
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | نوع التكامل |
| lowerLimit | [System::String](../../../system/string/) | الحد الأدنى للتكامل |
| upperLimit | [System::String](../../../system/string/) | الحد الأعلى للتكامل |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | موقع الحدود |

### قيمة الإرجاع
مثيل جديد من النوع [IMathNaryOperator](../../imathnaryoperator/)

## ملاحظات



مثال:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5", MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes, System::String, System::String) طريقة

يأخذ التكامل

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit) override
```

### المعلمات
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | نوع التكامل |
| lowerLimit | [System::String](../../../system/string/) | الحد الأدنى للتكامل |
| upperLimit | [System::String](../../../system/string/) | الحد الأعلى للتكامل |

### قيمة الإرجاع
مثيل جديد من النوع [IMathNaryOperator](../../imathnaryoperator/)

## ملاحظات



مثال:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5");
```

## انظر أيضا

* Enum [MathIntegralTypes](../../mathintegraltypes/)
* Enum [MathLimitLocations](../../mathlimitlocations/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathNaryOperator](../../imathnaryoperator/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)