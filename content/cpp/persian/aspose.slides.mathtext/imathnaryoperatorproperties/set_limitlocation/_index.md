---
title: set_LimitLocation()
second_title: Aspose.Slides برای مرجع API C++
description: محل قرارگیری حدود (پایین‌نویس و بالانویس)
type: docs
weight: 40
url: /fa/aspose.slides.mathtext/imathnaryoperatorproperties/set_limitlocation/
---
## IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations) متد

محل قرارگیری حدود (پایین‌نویس و بالانویس)

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations value)=0
```

## توضیحات

مثال:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## مراجع

* Enum [MathLimitLocations](../../mathlimitlocations/)
* کلاس [IMathNaryOperatorProperties](../)
* فضای نام [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)