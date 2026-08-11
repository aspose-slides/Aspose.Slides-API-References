---
title: set_SeparatorCharacter()
second_title: Aspose.Slides برای C++ مرجع API
description: "Delimiter Separator Character مشخص می‌کند که چه کاراکتری آرگومان‌ها را در شیء delimiter جدا می‌کند. پیش‌فرض: '|'."
type: docs
weight: 53
url: /fa/aspose.slides.mathtext/imathdelimiter/set_separatorcharacter/
---
## IMathDelimiter::set_SeparatorCharacter(char16_t) متد

Delimiter Separator Character مشخص می‌کند که چه کاراکتری آرگومان‌ها را در شیء delimiter جدا می‌کند. پیش‌فرض: '|'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_SeparatorCharacter(char16_t value)=0
```

## توضیحات

مثال:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## موارد مرتبط

* کلاس [IMathDelimiter](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)