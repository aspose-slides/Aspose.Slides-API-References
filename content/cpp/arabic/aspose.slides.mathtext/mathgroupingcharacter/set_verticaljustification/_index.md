---
title: set_VerticalJustification()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "محاذاة عمودية للحرف المجمع. يحدد محاذاة الكائن بالنسبة إلى خط الأساس. على سبيل المثال، عندما يكون الحرف المجمع أعلى الكائن، فإن VerticalJustification للـ Top يدل على أن أعلى الكائن يقع على خط الأساس؛ عندما يتم تعيين VerticalJustification إلى Bottom، يكون أسفل الكائن على خط الأساس. الافتراضي: Bottom عندما Position=Top، و Top عندما Position=Bottom"
type: docs
weight: 79
url: /ar/aspose.slides.mathtext/mathgroupingcharacter/set_verticaljustification/
---
## MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) طريقة

المحاذاة العمودية للحرف المجموعة. يحدد محاذاة الكائن بالنسبة إلى خط القاعدة. على سبيل المثال، عندما يكون الحرف المجموعة أعلى الكائن، فإن VerticalJustification لـ Top يدل على أن أعلى الكائن يقع على خط القاعدة؛ عندما يتم تعيين VerticalJustification إلى Bottom، يكون أسفل الكائن على خط القاعدة. الافتراضي: Bottom لـ Position=Top، و Top لـ Position=Bottom

```cpp
void Aspose::Slides::MathText::MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value) override
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
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)