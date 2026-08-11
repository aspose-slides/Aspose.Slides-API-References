---
title: set_VerticalJustification()
second_title: Aspose.Slides لمرجع API C++
description: "محاذاة عمودية للرمز المجمع. يحدد محاذاة الكائن بالنسبة إلى خط الأساس. على سبيل المثال، عندما يكون الرمز المجمع فوق الكائن، فإن VerticalJustification من Top يعني أن الجزء العلوي من الكائن يقع على خط الأساس؛ وعندما يتم تعيين VerticalJustification إلى Bottom، يكون الجزء السفلي من الكائن على خط الأساس. Default: Bottom عندما Position=Top، وTop عندما Position=Bottom"
type: docs
weight: 79
url: /ar/aspose.slides.mathtext/imathgroupingcharacter/set_verticaljustification/
---
## IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) طريقة

محاذاة عمودية للرمز المجمع. يحدد محاذاة الكائن بالنسبة إلى خط الأساس. على سبيل المثال، عندما يكون الرمز المجمع فوق الكائن، فإن VerticalJustification من Top يعني أن الجزء العلوي من الكائن يقع على خط الأساس؛ وعندما يتم تعيين VerticalJustification إلى Bottom، يكون الجزء السفلي من الكائن على خط الأساس. الافتراضي: Bottom عندما Position=Top، وTop عندما Position=Bottom

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value)=0
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
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)