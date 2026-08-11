---
title: get_Name()
second_title: Aspose.Slides برای مرجع API C++
description: نام تابع. به عنوان مثال، نام توابع sin و cos هستند
type: docs
weight: 1
url: /fa/aspose.slides.mathtext/mathfunction/get_name/
---
## MathFunction::get_Name() متد

نام تابع. به عنوان مثال، نام توابع sin و cos هستند

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Name() override
```

## یادداشت‌ها

مثال: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathFunction](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)