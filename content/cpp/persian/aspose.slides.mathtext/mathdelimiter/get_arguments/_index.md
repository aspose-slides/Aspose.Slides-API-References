---
title: get_Arguments()
second_title: Aspose.Slides برای مرجع API C++
description: یک یا چند عنصر ریاضی که با کاراکترهای جداکننده تفکیک شده‌اند
type: docs
weight: 1
url: /fa/aspose.slides.mathtext/mathdelimiter/get_arguments/
---
## MathDelimiter::get_Arguments() متد

یک یا چند عنصر ریاضی که با کاراکترهای جداکننده تفکیک شده‌اند

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathDelimiter::get_Arguments() override
```

## توضیح

مثال:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
auto arguments = delimiter->get_Arguments();
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElementCollection](../../imathelementcollection/)
* کلاس [MathDelimiter](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)