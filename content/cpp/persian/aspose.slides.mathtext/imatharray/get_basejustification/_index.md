---
title: get_BaseJustification()
second_title: مرجع API Aspose.Slides برای C++
description: "محاذیر آرایه نسبت به متن اطراف را مشخص می‌کند. متن خارج از آرایه می‌تواند با پایین، بالا یا مرکز یک شیء آرایه هم‌راست شود. مقدار پیش‌فرض: Center"
type: docs
weight: 14
url: /fa/aspose.slides.mathtext/imatharray/get_basejustification/
---
## IMathArray::get_BaseJustification() متد

انطباق آرایه نسبت به متن اطراف را مشخص می‌کند. متن خارج از آرایه می‌تواند با پایین، بالا یا مرکز یک شیء آرایه هم‌راست شود. مقدار پیش‌فرض: Center

```cpp
virtual MathVerticalAlignment Aspose::Slides::MathText::IMathArray::get_BaseJustification()=0
```

## توضیحات


مثال: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## همچنین ببینید

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* کلاس [IMathArray](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)