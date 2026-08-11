---
title: set_EndingCharacter()
second_title: مرجع API Aspose.Slides برای C++
description: "Delimiter Ending Character مشخص می‌کند که کاراکتر انتهایی یا بستن delimiter باشد. delimiters ریاضی کاراکترهای محاط‌کننده‌ای مانند پرانتزها، کروشه‌ها و آکولادها هستند. مقدار پیش‌فرض: ')'."
type: docs
weight: 79
url: /fa/aspose.slides.mathtext/mathdelimiter/set_endingcharacter/
---
## MathDelimiter::set_EndingCharacter(char16_t) متد

Delimiter Ending Character مشخص می‌کند که کاراکتر انتهایی یا بستن چه کاری باشد. delimiters ریاضی کاراکترهای محاط‌کننده‌ای مانند پرانتزها، کروشه‌ها و آکولادها هستند. مقدار پیش‌فرض: ')'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_EndingCharacter(char16_t value) override
```

## توضیحات

مثال:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## موارد مرتبط

* کلاس [MathDelimiter](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)