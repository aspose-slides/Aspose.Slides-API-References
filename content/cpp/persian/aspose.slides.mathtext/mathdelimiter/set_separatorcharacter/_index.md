---
title: set_SeparatorCharacter()
second_title: مرجع API Aspose.Slides برای C++
description: "کاراکتر جداکننده‌ی Delimiter مشخص می‌کند که کدام کاراکتر آرگومان‌ها را در شیء delimiter جدا می‌کند. مقدار پیش‌فرض: '|'."
type: docs
weight: 53
url: /fa/aspose.slides.mathtext/mathdelimiter/set_separatorcharacter/
---
## MathDelimiter::set_SeparatorCharacter(char16_t) method


کاراکتر جداکننده مشخص می‌کند که کدام کاراکتر آرگومان‌ها را در شیء delimiter جدا می‌کند. مقدار پیش‌فرض: '|'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_SeparatorCharacter(char16_t value) override
```

## توضیحات


مثال: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## موارد مرتبط

* کلاس [MathDelimiter](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)