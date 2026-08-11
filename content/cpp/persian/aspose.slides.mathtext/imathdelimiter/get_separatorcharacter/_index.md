---
title: get_SeparatorCharacter()
second_title: مرجع API Aspose.Slides برای C++
description: "ویژگی Delimiter Separator Character کاراکتری را مشخص می‌کند که آرگومان‌ها را در شیء delimiter جدا می‌کند. مقدار پیش‌فرض: '|'."
type: docs
weight: 40
url: /fa/aspose.slides.mathtext/imathdelimiter/get_separatorcharacter/
---
## IMathDelimiter::get_SeparatorCharacter() متد

ویژگی Delimiter Separator Character کاراکتری را مشخص می‌کند که آرگومان‌ها را در شیء delimiter جدا می‌کند. مقدار پیش‌فرض: '|'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_SeparatorCharacter()=0
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