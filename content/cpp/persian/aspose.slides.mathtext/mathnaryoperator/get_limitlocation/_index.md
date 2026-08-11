---
title: get_LimitLocation()
second_title: Aspose.Slides برای مرجع API C++
description: موقعیت محدودها (پایین‌نویس و بالانویس)
type: docs
weight: 66
url: /fa/aspose.slides.mathtext/mathnaryoperator/get_limitlocation/
---
## MathNaryOperator::get_LimitLocation() متد


موقعیت محدودها (پایین‌نویس و بالانویس)

```cpp
MathLimitLocations Aspose::Slides::MathText::MathNaryOperator::get_LimitLocation() override
```

## ملاحظات


مثال: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## موارد مرتبط

* Enum [MathLimitLocations](../../mathlimitlocations/)
* کلاس [MathNaryOperator](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)