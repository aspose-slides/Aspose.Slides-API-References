---
title: get_BeginningCharacter()
second_title: مرجع API Aspose.Slides برای C++
description: "کاراکتر شروع جداکننده، کاراکتر آغاز یا باز جداکننده را مشخص می‌کند. جداکننده‌های ریاضی، کاراکترهای بسته‌کننده‌ای مانند پرانتز، کروشه و آکولاد هستند. مقدار پیش‌فرض: '('."
type: docs
weight: 14
url: /fa/aspose.slides.mathtext/mathdelimiter/get_beginningcharacter/
---
## MathDelimiter::get_BeginningCharacter() متد

کاراکتر شروع جداکننده، کاراکتر جداکنندهٔ آغاز یا باز را مشخص می‌کند. جداکننده‌های ریاضی، کاراکترهای بسته‌کننده‌ای مانند پرانتز، کروشه و آکولاد هستند. مقدار پیش‌فرض: '('.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_BeginningCharacter() override
```

## ملاحظات

مثال:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## بخش‌های مرتبط

* کلاس [MathDelimiter](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)