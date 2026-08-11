---
title: set_BeginningCharacter()
second_title: مرجع API Aspose.Slides برای C++
description: "کاراکتر آغازگر جداکننده، شروع یا کاراکتر باز شدن جداکننده را مشخص می‌کند. جداکننده‌های ریاضی شامل کاراکترهای بسته‌سازی مانند پرانتزها، کروشه‌ها و آکولادها هستند. مقدار پیش‌فرض: '('."
type: docs
weight: 27
url: /fa/aspose.slides.mathtext/mathdelimiter/set_beginningcharacter/
---
## MathDelimiter::set_BeginningCharacter(char16_t) متد


کاراکتر آغازگر جداکننده، کاراکتر شروع یا باز شدن جداکننده را مشخص می‌کند. جداکننده‌های ریاضی شامل کاراکترهای بسته‌سازی مانند پرانتزها، کروشه‌ها و آکولادها هستند. مقدار پیش‌فرض: '('.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_BeginningCharacter(char16_t value) override
```

## توضیحات


مثال: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## موارد مرتبط

* کلاس [MathDelimiter](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)