---
title: get_LimitLocation()
second_title: مرجع API Aspose.Slides برای C++
description: مکان حدها (زیرنویس و بالانویس)
type: docs
weight: 27
url: /fa/aspose.slides.mathtext/imathnaryoperatorproperties/get_limitlocation/
---
## IMathNaryOperatorProperties::get_LimitLocation() متد

موقعیت حدها (زیرنویس و بالانویس)

```cpp
virtual MathLimitLocations Aspose::Slides::MathText::IMathNaryOperatorProperties::get_LimitLocation()=0
```

## توضیحات

مثال:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## موارد مرتبط

* Enum [MathLimitLocations](../../mathlimitlocations/)
* کلاس [IMathNaryOperatorProperties](../)
* فضای نام [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)