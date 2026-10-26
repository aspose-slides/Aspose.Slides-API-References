---
title: get_VerticalJustification()
second_title: راهنمای API Aspose.Slides برای C++
description: "هم تراست عمودی کاراکتر گروه. تراز شیء نسبت به خط پایه را مشخص می‌کند. برای مثال، وقتی کاراکتر گروه بالای شیء باشد، VerticalJustification مقدار Top نشان می‌دهد که بالای شیء بر روی خط پایه قرار می‌گیرد؛ وقتی VerticalJustification روی Bottom تنظیم شود، پایین شیء بر روی خط پایه است. پیش‌فرض: Bottom برای Position=Top و Top برای Position=Bottom"
type: docs
weight: 66
url: /fa/aspose.slides.mathtext/imathgroupingcharacter/get_verticaljustification/
---
## IMathGroupingCharacter::get_VerticalJustification() متد

هم تراست عمودی کاراکتر گروه. تراز شیء نسبت به خط پایه را مشخص می‌کند. برای مثال، وقتی کاراکتر گروه بالای شیء باشد، VerticalJustification مقدار Top نشان می‌دهد که بالای شیء بر روی خط پایه قرار می‌گیرد؛ وقتی VerticalJustification بر روی Bottom تنظیم شود، پایین شیء بر روی خط پایه است. پیش‌فرض: Bottom برای Position=Top و Top برای Position=Bottom

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_VerticalJustification()=0
```

## توضیحات


مثال: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## موارد مرتبط

* شمارنده [MathTopBotPositions](../../mathtopbotpositions/)
* کلاس [IMathGroupingCharacter](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)