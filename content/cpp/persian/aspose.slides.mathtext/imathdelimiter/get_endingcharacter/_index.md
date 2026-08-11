---
title: get_EndingCharacter()
second_title: مرجع API Aspose.Slides برای C++
description: "کاراکتر انتهایی جداکننده، کاراکتر پایان یا بسته شدن جداکننده را مشخص می‌کند. جداکننده‌های ریاضی کاراکترهای احاطه‌کننده‌ای هستند، مانند پرانتز، کروشه و آکولاد. پیش‌فرض: ')'."
type: docs
weight: 66
url: /fa/aspose.slides.mathtext/imathdelimiter/get_endingcharacter/
---
## IMathDelimiter::get_EndingCharacter() متد

Delimiter Ending Character کاراکتر انتهایی یا بسته‌کنندهٔ جداکننده را مشخص می‌کند. جداکننده‌های ریاضی کاراکترهای احاطه‌کننده‌ای هستند که شامل پرانتز، کروشه و آکولاد می‌شوند. پیش‌فرض: ')'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_EndingCharacter()=0
```

## ملاحظات

مثال: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## موارد مرتبط

* کلاس [IMathDelimiter](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)