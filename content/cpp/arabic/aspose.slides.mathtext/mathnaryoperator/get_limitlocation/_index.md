---
title: get_LimitLocation()
second_title: Aspose.Slides لـ C++ مرجع API
description: موقع الحدود (النص السفلي والنص العلوي)
type: docs
weight: 66
url: /ar/aspose.slides.mathtext/mathnaryoperator/get_limitlocation/
---
## MathNaryOperator::get_LimitLocation() طريقة


موقع الحدود (النص السفلي والنص العلوي)

```cpp
MathLimitLocations Aspose::Slides::MathText::MathNaryOperator::get_LimitLocation() override
```

## ملاحظات


مثال:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## انظر أيضًا

* تعداد [MathLimitLocations](../../mathlimitlocations/)
* فئة [MathNaryOperator](../)
* مساحة اسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)