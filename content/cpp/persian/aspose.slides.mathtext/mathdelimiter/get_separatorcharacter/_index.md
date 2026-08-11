---
title: get_SeparatorCharacter()
second_title: Aspose.Slides برای C++ مرجع API
description: "Delimiter Separator Character کاراکتری را مشخص می‌کند که آرگومان‌ها را در شیء delimiter جدا می‌کند. مقدار پیش‌فرض: '|'."
type: docs
weight: 40
url: /fa/aspose.slides.mathtext/mathdelimiter/get_separatorcharacter/
---
## MathDelimiter::get_SeparatorCharacter() متد


Delimiter Separator Character specifies the character that separates arguments in the delimiter object. The default: '|'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_SeparatorCharacter() override
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