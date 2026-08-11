---
title: set_RowSpacing()
second_title: مرجع API Aspose.Slides برای C++
description: "فاصله بین سطرهای یک آرایه. این فقط زمانی استفاده می‌شود که RowSpacingRule برابر ۳ تنظیم شده باشد. دقیقاً در این حالت واحد اندازه‌گیری نقطه است یا Multiple که در این حالت واحد نیم‌خط است. پیش‌فرض: 0"
type: docs
weight: 131
url: /fa/aspose.slides.mathtext/matharray/set_rowspacing/
---
## MathArray::set_RowSpacing(uint32_t) متد


فاصله بین سطرهای یک آرایه. این فقط زمانی استفاده می‌شود که RowSpacingRule برابر ۳ باشد. دقیقاً در این حالت واحد اندازه‌گیری نقطه است یا Multiple که در این حالت واحد نصف خط است. پیش‌فرض: 0

```cpp
void Aspose::Slides::MathText::MathArray::set_RowSpacing(uint32_t value) override
```

## ملاحظات


مثال: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## موارد دیگر

* کلاس [MathArray](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)