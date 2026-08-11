---
title: set_LimitLocation()
second_title: مرجع API Aspose.Slides برای C++
description: محل محدودیت‌ها (پایین‌نویس و بالانویس)
type: docs
weight: 79
url: /fa/aspose.slides.mathtext/mathnaryoperator/set_limitlocation/
---
## MathNaryOperator::set_LimitLocation(MathLimitLocations) متد


محل محدودیت‌ها (پایین‌نویس و بالانویس)

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_LimitLocation(MathLimitLocations value) override
```

## توضییات


مثال: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## مراجع

* Enum [MathLimitLocations](../../mathlimitlocations/)
* کلاس [MathNaryOperator](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)