---
title: set_VerticalJustification()
second_title: Aspose.Slides برای مرجع API C++
description: "تراز عمودی کاراکتر گروه. تنظیمات تراز شیء نسبت به خط پایه را مشخص می‌کند. برای مثال، هنگامی که کاراکتر گروه بالای شیء قرار دارد، مقدار VerticalJustification برابر Top نشان می‌دهد که بالای شیء بر روی خط پایه قرار می‌گیرد؛ وقتی VerticalJustification برابر Bottom باشد، پایین شیء بر روی خط پایه است. پیش‌فرض: Bottom برای Position=Top و Top برای Position=Bottom"
type: docs
weight: 79
url: /fa/aspose.slides.mathtext/mathgroupingcharacter/set_verticaljustification/
---
## MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) متد

تراز عمودی کاراکتر گروه. تنظیمات تراز شیء نسبت به خط پایه را مشخص می‌کند. برای مثال، هنگامی که کاراکتر گروه بالای شیء قرار دارد، مقدار VerticalJustification برابر Top نشان می‌دهد که بالای شیء بر روی خط پایه قرار می‌گیرد؛ وقتی VerticalJustification برابر Bottom باشد، پایین شیء بر روی خط پایه است. پیش‌فرض: Bottom برای Position=Top و Top برای Position=Bottom

```cpp
void Aspose::Slides::MathText::MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value) override
```

## ملاحظات


مثال: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## همچنین ببینید

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* کلاس [MathGroupingCharacter](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)