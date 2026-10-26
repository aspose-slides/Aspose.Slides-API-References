---
title: get_VerticalJustification()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "محاذاة عمودية لحرف المجموعة. يحدد محاذاة الكائن بالنسبة لخط القاعدة. على سبيل المثال، عندما يكون حرف المجموعة فوق الكائن، فإن VerticalJustification بـ Top يعني أن الجزء العلوي من الكائن يقع على خط القاعدة؛ وعند ضبط VerticalJustification إلى Bottom، يكون الجزء السفلي من الكائن على خط القاعدة. الافتراضي: Bottom عندما Position=Top، و Top عندما Position=Bottom"
type: docs
weight: 66
url: /ar/aspose.slides.mathtext/imathgroupingcharacter/get_verticaljustification/
---
## طريقة IMathGroupingCharacter::get_VerticalJustification()

محاذاة عمودية لحرف المجموعة. يحدد محاذاة الكائن بالنسبة لخط القاعدة. على سبيل المثال، عندما يكون حرف المجموعة فوق الكائن، فإن VerticalJustification بـ Top يعني أن الجزء العلوي من الكائن يقع على خط القاعدة؛ وعند ضبط VerticalJustification إلى Bottom، يكون الجزء السفلي من الكائن على خط القاعدة. الافتراضي: Bottom عندما Position=Top، و Top عندما Position=Bottom

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_VerticalJustification()=0
```

## ملاحظات

مثال: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## انظر أيضًا

* تعداد [MathTopBotPositions](../../mathtopbotpositions/)
* فئة [IMathGroupingCharacter](../)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)