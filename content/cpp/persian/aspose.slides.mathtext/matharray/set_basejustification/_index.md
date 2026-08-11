---
title: set_BaseJustification()
second_title: Aspose.Slides برای C++ مرجع API
description: "ترازبندی آرایه نسبت به متن اطراف را تعیین می‌کند. متن خارج از آرایه می‌تواند با پایین، بالا یا مرکز شیء آرایه هم‌تراز شود. مقدار پیش‌فرض: Center"
type: docs
weight: 27
url: /fa/aspose.slides.mathtext/matharray/set_basejustification/
---
## MathArray::set_BaseJustification(MathVerticalAlignment) متد


مشخص می‌کند که تنظیمات تراز آرایه نسبت به متن اطراف چگونه باشد. متن خارج از آرایه می‌تواند با پایین، بالا یا مرکز شیء آرایه هم‌ترازی شود. مقدار پیش‌فرض: Center

```cpp
void Aspose::Slides::MathText::MathArray::set_BaseJustification(MathVerticalAlignment value) override
```

## توضیحات


مثال: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## موارد مرتبط

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* کلاس [MathArray](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)