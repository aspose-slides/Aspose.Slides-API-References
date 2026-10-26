---
title: set_BaseJustification()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يحدد محاذاة المصفوفة بالنسبة للنص المحيط. يمكن محاذاة النص خارج المصفوفة إلى الأسفل أو الأعلى أو المركز لكائن المصفوفة. القيمة الافتراضية: Center"
type: docs
weight: 27
url: /ar/aspose.slides.mathtext/imatharray/set_basejustification/
---
## IMathArray::set_BaseJustification(MathVerticalAlignment) طريقة

يحدد محاذاة المصفوفة بالنسبة للنص المحيط. يمكن محاذاة النص خارج المصفوفة إلى الأسفل أو الأعلى أو المركز لكائن المصفوفة. القيمة الافتراضية: Center

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_BaseJustification(MathVerticalAlignment value)=0
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
* نطاق الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)