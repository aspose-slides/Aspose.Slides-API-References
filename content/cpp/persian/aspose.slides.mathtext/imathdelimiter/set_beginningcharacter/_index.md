---
title: set_BeginningCharacter()
second_title: مرجع API Aspose.Slides برای C++
description: "کاراکتر آغازگر جداساز (Delimiter Beginning Character) مشخص می‌کند که کاراکتر مرز اولیه، یعنی کاراکتر باز شدن، چیست. جداسازهای ریاضی کاراکترهای بسته‌کننده‌ای هستند که مانند پرانتزها، کروشه‌ها و آکولادها می‌باشند. مقدار پیش‌فرض: '('."
type: docs
weight: 27
url: /fa/aspose.slides.mathtext/imathdelimiter/set_beginningcharacter/
---
## IMathDelimiter::set_BeginningCharacter(char16_t) متد

Delimiter Beginning Character مشخص می‌کند که کاراکتر مرز اولیه، یعنی کاراکتر باز شدن، چیست. مرزهای ریاضی کاراکترهای بسته‌کننده‌ای هستند که مانند پرانتزها، کروشه‌ها و آکولادها می‌باشند. مقدار پیش‌فرض: '('.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_BeginningCharacter(char16_t value)=0
```

## توضیحات

مثال:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## همچنین

* کلاس [IMathDelimiter](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)