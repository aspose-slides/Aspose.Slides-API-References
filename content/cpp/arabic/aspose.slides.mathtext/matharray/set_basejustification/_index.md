---
title: set_BaseJustification()
second_title: مرجع API لـ Aspose.Slides لـ C++
description: "يحدد محاذاة المصفوفة بالنسبة للنص المحيط. يمكن محاذاة النص خارج المصفوفة إلى الأسفل أو الأعلى أو وسط كائن المصفوفة. القيمة الافتراضية: Center"
type: docs
weight: 27
url: /ar/aspose.slides.mathtext/matharray/set_basejustification/
---
## MathArray::set_BaseJustification(MathVerticalAlignment) طريقة

يحدد محاذاة المصفوفة بالنسبة للنص المحيط. يمكن محاذاة النص خارج المصفوفة إلى أسفل أو أعلى أو وسط كائن المصفوفة. القيمة الافتراضية: Center

```cpp
void Aspose::Slides::MathText::MathArray::set_BaseJustification(MathVerticalAlignment value) override
```

## ملاحظات

مثال:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## انظر أيضًا

* تعداد [MathVerticalAlignment](../../mathverticalalignment/)
* فئة [MathArray](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)