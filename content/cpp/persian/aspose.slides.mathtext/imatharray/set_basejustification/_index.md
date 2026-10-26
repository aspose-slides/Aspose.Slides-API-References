---
title: set_BaseJustification()
second_title: مرجع API Aspose.Slides برای C++
description: "مرتب‌سازی هم‌راستایی آرایه نسبت به متن اطراف را تعیین می‌کند. متن خارج از آرایه می‌تواند با پایین، بالا یا مرکز یک شیء آرایه هم‌راستا شود. مقدار پیش‌فرض: Center"
type: docs
weight: 27
url: /fa/aspose.slides.mathtext/imatharray/set_basejustification/
---
## IMathArray::set_BaseJustification(MathVerticalAlignment) متد

مرتب‌سازی هم‌راستایی آرایه نسبت به متن اطراف را تعیین می‌کند. متن خارج از آرایه می‌تواند با پایین، بالا یا مرکز یک شیء آرایه هم‌راستا شود. مقدار پیش‌فرض: Center

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_BaseJustification(MathVerticalAlignment value)=0
```

## توضیحات


مثال: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## موارد مرتبط

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* کلاس [IMathArray](../)
* فضای نام [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)