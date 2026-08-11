---
title: get_Arguments()
second_title: مرجع API Aspose.Slides برای C++
description: مجموع آیتم‌های آرایه
type: docs
weight: 1
url: /fa/aspose.slides.mathtext/matharray/get_arguments/
---
## MathArray::get_Arguments() متد


مجموع آیتم‌های آرایه

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathArray::get_Arguments() override
```

## توضیحات


مثال:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElementCollection](../../imathelementcollection/)
* کلاس [MathArray](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)