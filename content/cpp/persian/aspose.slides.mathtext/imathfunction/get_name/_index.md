---
title: get_Name()
second_title: مرجع API Aspose.Slides برای C++
description: نام تابع برای مثال، نام توابع sin و cos هستند
type: docs
weight: 1
url: /fa/aspose.slides.mathtext/imathfunction/get_name/
---
## IMathFunction::get_Name() متد


نام تابع برای مثال، نام توابع sin و cos هستند

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Name()=0
```

## توضیحات


مثال: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## مراجع

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [IMathFunction](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)