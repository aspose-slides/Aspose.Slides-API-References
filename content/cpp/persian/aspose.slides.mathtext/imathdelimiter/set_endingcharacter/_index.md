---
title: set_EndingCharacter()
second_title: Aspose.Slides برای C++ مرجع API
description: "کاراکتر پایان جداکننده (Delimiter Ending Character) تعیین می‌کند که کاراکتر پایان یا بسته شدن جداکننده چیست. جداکننده‌های ریاضی کاراکترهای احاطه‌کننده‌ای مانند پرانتز، کروشه و آکولاد هستند. مقدار پیش‌فرض: ')'."
type: docs
weight: 79
url: /fa/aspose.slides.mathtext/imathdelimiter/set_endingcharacter/
---
## IMathDelimiter::set_EndingCharacter(char16_t) متد

Delimiter Ending Character مشخص می‌کند که کاراکتر پایان یا بسته شدن جداکننده چیست. جداکننده‌های ریاضی کاراکترهای محاط‌کننده‌ای مانند پرانتز، کروشه و آکولاد هستند. مقدار پیش‌فرض: ')'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_EndingCharacter(char16_t value)=0
```

## ملاحظات

مثال: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## موارد مرتبط

* کلاس [IMathDelimiter](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)