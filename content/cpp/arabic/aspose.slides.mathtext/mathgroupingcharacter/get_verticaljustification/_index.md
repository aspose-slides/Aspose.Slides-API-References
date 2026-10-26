---
title: get_VerticalJustification()
second_title: Aspose.Slides للـ C++ مرجع API
description: "محاذاة عمودية لحرف المجموعة. تحدد موضع الكائن بالنسبة لخط الأساس. على سبيل المثال، عندما يكون حرف المجموعة أعلى الكائن، يشير VerticalJustification بقيمة Top إلى أن أعلى الكائن يقع على خط الأساس؛ عندما يتم تعيين VerticalJustification إلى Bottom، يكون أسفل الكائن على خط الأساس. القيمة الافتراضية: Bottom عندما Position=Top، وTop عندما Position=Bottom"
type: docs
weight: 66
url: /ar/aspose.slides.mathtext/mathgroupingcharacter/get_verticaljustification/
---
## MathGroupingCharacter::get_VerticalJustification() طريقة

محاذاة عمودية لحرف المجموعة. تحدد موضع الكائن بالنسبة لخط الأساس. على سبيل المثال، عندما يكون حرف المجموعة فوق الكائن، فإن VerticalJustification بقيمة Top يعني أن أعلى الكائن يقع على خط الأساس؛ عندما يتم تعيين VerticalJustification إلى Bottom، يكون أسفل الكائن على خط الأساس. القيمة الافتراضية: Bottom عندما Position=Top، و Top عندما Position=Bottom

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathGroupingCharacter::get_VerticalJustification() override
```

## ملاحظات


مثال:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## انظر أيضًا

* تعداد [MathTopBotPositions](../../mathtopbotpositions/)
* فئة [MathGroupingCharacter](../)
* نطاق الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)