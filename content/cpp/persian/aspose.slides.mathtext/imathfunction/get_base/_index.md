---
title: get_Base()
second_title: Aspose.Slides برای مرجع API C++
description: آرگومان تابع
type: docs
weight: 14
url: /fa/aspose.slides.mathtext/imathfunction/get_base/
---
## IMathFunction::get_Base() متد


آرگومان تابع

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Base()=0
```

## توضیحات


مثال:
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [IMathFunction](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)