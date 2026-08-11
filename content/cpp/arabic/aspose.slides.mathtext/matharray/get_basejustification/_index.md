---
title: get_BaseJustification()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يحدد محاذاة المصفوفة بالنسبة للنص المحيط. يمكن محاذاة النص خارج المصفوفة إلى الأسفل أو الأعلى أو إلى مركز كائن المصفوفة. القيمة الافتراضية: الوسط"
type: docs
weight: 14
url: /ar/aspose.slides.mathtext/matharray/get_basejustification/
---
## MathArray::get_BaseJustification() طريقة

يحدد محاذاة المصفوفة بالنسبة للنص المحيط. يمكن محاذاة النص خارج المصفوفة إلى الأسفل أو الأعلى أو إلى مركز كائن المصفوفة. القيمة الافتراضية: الوسط

```cpp
MathVerticalAlignment Aspose::Slides::MathText::MathArray::get_BaseJustification() override
```

## ملاحظات

مثال:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## أنظر أيضًا

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* فئة [MathArray](../)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)