---
title: get_Arguments()
second_title: مرجع API Aspose.Slides برای C++
description: یک یا چند عنصر ریاضی که با کاراکترهای جداکننده از هم جدا شده‌اند
type: docs
weight: 1
url: /fa/aspose.slides.mathtext/imathdelimiter/get_arguments/
---
## IMathDelimiter::get_Arguments() متد

یک یا چند عنصر ریاضی که با کاراکترهای جداکننده از هم جدا شده‌اند

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathDelimiter::get_Arguments()=0
```

## توضیحات

مثال:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
auto arguments = delimiter->get_Arguments();
```

## همچنین ببینید

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElementCollection](../../imathelementcollection/)
* کلاس [IMathDelimiter](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)