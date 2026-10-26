---
title: get_VerticalJustification()
second_title: مرجع API Aspose.Slides برای C++
description: "تراست عمودی کاراکتر گروه. جهت‌گیری شیء نسبت به خط پایه را مشخص می‌کند. برای مثال، وقتی کاراکتر گروه بالای شیء قرار دارد، VerticalJustification مقدار Top نشان می‌دهد که بالای شیء بر روی خط پایه قرار می‌گیرد؛ وقتی VerticalJustification روی Bottom تنظیم می‌شود، پایین شیء بر روی خط پایه قرار می‌گیرد پیش‌فرض: Bottom برای Position=Top و Top برای Position=Bottom"
type: docs
weight: 66
url: /fa/aspose.slides.mathtext/mathgroupingcharacter/get_verticaljustification/
---
## MathGroupingCharacter::get_VerticalJustification() متد

تراست عمودی کاراکتر گروه. جهت‌گیری شیء نسبت به خط پایه را مشخص می‌کند. برای مثال، هنگامی که کاراکتر گروه بالای شیء قرار دارد، VerticalJustification مقدار Top نشان می‌دهد که بالای شیء بر روی خط پایه قرار می‌گیرد؛ وقتی VerticalJustification روی Bottom تنظیم می‌شود، پایین شیء بر روی خط پایه قرار می‌گیرد. پیش‌فرض: Bottom برای Position=Top، و Top برای Position=Bottom

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathGroupingCharacter::get_VerticalJustification() override
```

## توضیحات


مثال: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## مراجع

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* کلاس [MathGroupingCharacter](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)