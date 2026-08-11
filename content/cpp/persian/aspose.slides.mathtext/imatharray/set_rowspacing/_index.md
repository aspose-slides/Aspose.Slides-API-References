---
title: set_RowSpacing()
second_title: مرجع API Aspose.Slides برای C++
description: "فاصله بین ردیف‌های یک آرایه فقط زمانی استفاده می‌شود که RowSpacingRule برابر 3 باشد. دقیقاً در این حالت واحد اندازه‌گیری نقطه است یا Multiple که در این صورت واحد اندازه‌گیری نیم‌خط است. پیش‌فرض: 0"
type: docs
weight: 131
url: /fa/aspose.slides.mathtext/imatharray/set_rowspacing/
---
## IMathArray::set_RowSpacing(uint32_t) متد

فاصله بین ردیف‌های یک آرایه فقط زمانی استفاده می‌شود که RowSpacingRule برابر 3 باشد. دقیقاً در این حالت واحد اندازه‌گیری نقطه است یا Multiple که در این صورت واحد اندازه‌گیری نیم‌خط است. پیش‌فرض: 0

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_RowSpacing(uint32_t value)=0
```

## توضیحات

مثال: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## مراجع

* کلاس [IMathArray](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)