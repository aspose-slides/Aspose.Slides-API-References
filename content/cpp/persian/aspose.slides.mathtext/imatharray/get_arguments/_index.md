---
title: get_Arguments()
second_title: مرجع API Aspose.Slides برای C++
description: مجموعه‌ای از آیتم‌های آرایه
type: docs
weight: 1
url: /fa/aspose.slides.mathtext/imatharray/get_arguments/
---
## IMathArray::get_Arguments() متد

مجموعه‌ای از آیتم‌های آرایه

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathArray::get_Arguments()=0
```

## توضیحات

مثال: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElementCollection](../../imathelementcollection/)
* کلاس [IMathArray](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)