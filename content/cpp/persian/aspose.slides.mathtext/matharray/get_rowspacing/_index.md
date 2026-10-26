---
title: get_RowSpacing()
second_title: Aspose.Slides برای C++ مرجع API
description: "فاصله بین ردیف‌های یک آرایه فقط زمانی استفاده می‌شود که RowSpacingRule برابر 3 باشد Exactly که در این صورت واحد اندازه‌گیری نقطه است یا Multiple که در این صورت واحد اندازه‌گیری نیم‌خط است. پیش‌فرض: 0"
type: docs
weight: 118
url: /fa/aspose.slides.mathtext/matharray/get_rowspacing/
---
## MathArray::get_RowSpacing() متد

فاصله بین ردیف‌های یک آرایه فقط زمانی استفاده می‌شود که RowSpacingRule برابر 3 باشد Exactly که در این حالت واحد اندازه‌گیری نقطه است یا Multiple که در این حالت واحد اندازه‌گیری نیم‌خط است. پیش‌فرض: 0

```cpp
uint32_t Aspose::Slides::MathText::MathArray::get_RowSpacing() override
```

## ملاحظات

مثال:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## مراجع

* کلاس [MathArray](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)