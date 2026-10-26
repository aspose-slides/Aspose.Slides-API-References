---
title: get_BaseJustification()
second_title: Aspose.Slides لـ C++ مرجع API
description: "يحدد محاذاة المصفوفة بالنسبة للنص المحيط. يمكن محاذاة النص خارج المصفوفة إلى الأسفل أو الأعلى أو إلى مركز كائن المصفوفة. القيمة الافتراضية: Center"
type: docs
weight: 14
url: /ar/aspose.slides.mathtext/imatharray/get_basejustification/
---
## IMathArray::get_BaseJustification() method


يحدد محاذاة المصفوفة بالنسبة للنص المحيط. يمكن محاذاة النص خارج المصفوفة إلى الأسفل أو الأعلى أو إلى وسط كائن المصفوفة. القيمة الافتراضية: Center

```cpp
virtual MathVerticalAlignment Aspose::Slides::MathText::IMathArray::get_BaseJustification()=0
```

## ملاحظات


مثال: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## انظر أيضًا

* تعداد [MathVerticalAlignment](../../mathverticalalignment/)
* فئة [IMathArray](../)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)