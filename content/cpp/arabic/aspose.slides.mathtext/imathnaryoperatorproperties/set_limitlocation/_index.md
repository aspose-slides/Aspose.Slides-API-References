---
title: set_LimitLocation()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: موقع الحدود (الكتابة السفلية والكتابة العلوية)
type: docs
weight: 40
url: /ar/aspose.slides.mathtext/imathnaryoperatorproperties/set_limitlocation/
---
## IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations) طريقة


موقع الحدود (الكتابة السفلية والكتابة العلوية)

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations value)=0
```

## ملاحظات


مثال:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperset);
```

## انظر أيضًا

* تعداد [MathLimitLocations](../../mathlimitlocations/)
* فئة [IMathNaryOperatorProperties](../)
* نطاق الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)