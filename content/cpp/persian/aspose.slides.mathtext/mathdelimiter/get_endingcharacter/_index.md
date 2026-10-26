---
title: get_EndingCharacter()
second_title: Aspose.Slides برای C++ مرجع API
description: "کاراکتر انتهایی محدود کننده مشخص می‌کند که کاراکتر انتهایی یا بسته‌کننده چه چیزی است. محدود کننده‌های ریاضی کاراکترهای احاطه‌کننده‌ای مانند پرانتزها، براکت‌ها و آکولادها هستند. مقدار پیش‌فرض: ')'."
type: docs
weight: 66
url: /fa/aspose.slides.mathtext/mathdelimiter/get_endingcharacter/
---
## MathDelimiter::get_EndingCharacter() متد

Delimiter Ending Character مشخص می‌کند که کاراکتر انتهایی یا بسته‌شوندهٔ محدود کننده چیست. محدود کننده‌های ریاضی کاراکترهای احاطه‌کننده‌ای مانند پرانتزها، براکت‌ها و آکولادها هستند. مقدار پیش‌فرض: ')'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_EndingCharacter() override
```

## توضیحات

مثال: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## موارد مرتبط

* کلاس [MathDelimiter](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)