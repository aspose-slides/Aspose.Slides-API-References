---
title: get_Base()
second_title: مرجع API Aspose.Slides برای C++
description: آرگومان تابع
type: docs
weight: 14
url: /fa/aspose.slides.mathtext/mathfunction/get_base/
---
## MathFunction::get_Base() متد


آرگومان تابع

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Base() override
```

## توضیحات


مثال: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathFunction](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)