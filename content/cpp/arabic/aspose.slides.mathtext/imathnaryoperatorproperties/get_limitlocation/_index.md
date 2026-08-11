---
title: get_LimitLocation()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: موقع الحدود (المؤشر السفلي والعلوي)
type: docs
weight: 27
url: /ar/aspose.slides.mathtext/imathnaryoperatorproperties/get_limitlocation/
---
## IMathNaryOperatorProperties::get_LimitLocation() طريقة


موقع الحدود (المؤشر السفلي والعلوي)

```cpp
virtual MathLimitLocations Aspose::Slides::MathText::IMathNaryOperatorProperties::get_LimitLocation()=0
```

## ملاحظات


مثال: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## انظر أيضاً

* التعداد [MathLimitLocations](../../mathlimitlocations/)
* الفئة [IMathNaryOperatorProperties](../)
* المجال [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)