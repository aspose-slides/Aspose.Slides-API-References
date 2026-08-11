---
title: set_LimitLocation()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: موقع الحدود (المؤشرات السفلية والعليا)
type: docs
weight: 79
url: /ar/aspose.slides.mathtext/mathnaryoperator/set_limitlocation/
---
## MathNaryOperator::set_LimitLocation(MathLimitLocations) method

موقع الحدود (المؤشرات السفلية والعليا)

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_LimitLocation(MathLimitLocations value) override
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
* مساحة الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)