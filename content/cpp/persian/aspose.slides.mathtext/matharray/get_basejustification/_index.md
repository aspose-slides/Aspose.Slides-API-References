---
title: get_BaseJustification()
second_title: مرجع API Aspose.Slides برای C++
description: "ترازبندی آرایه نسبت به متن اطراف را مشخص می‌کند. متن خارج از آرایه می‌تواند با پایین، بالا یا مرکز یک شیء آرایه هم‌راستا شود. مقدار پیش‌فرض: Center"
type: docs
weight: 14
url: /fa/aspose.slides.mathtext/matharray/get_basejustification/
---
## MathArray::get_BaseJustification() متد

ترازبندی آرایه نسبت به متن اطراف را مشخص می‌کند. متن خارج از آرایه می‌تواند با پایین، بالا یا مرکز یک شیء آرایه هم‌راستا شود. مقدار پیش‌فرض: Center

```cpp
MathVerticalAlignment Aspose::Slides::MathText::MathArray::get_BaseJustification() override
```

## نکات

مثال:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## موارد مرتبط

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Class [MathArray](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)