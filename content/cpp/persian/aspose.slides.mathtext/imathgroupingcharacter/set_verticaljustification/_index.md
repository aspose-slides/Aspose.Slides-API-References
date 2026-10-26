---
title: set_VerticalJustification()
second_title: مرجع API Aspose.Slides برای C++
description: "هم‌ترازی عمودی کاراکتر گروه. تنظیم تراز شیء نسبت به خط پایه را مشخص می‌کند. به عنوان مثال، هنگامی که کاراکتر گروه بالای شیء باشد، VerticalJustification مقدار Top به این معنی است که بالای شیء بر روی خط پایه قرار می‌گیرد؛ وقتی VerticalJustification به Bottom تنظیم شود، پایین شیء بر روی خط پایه قرار می‌گیرد. پیش‌فرض: Bottom برای Position=Top و Top برای Position=Bottom"
type: docs
weight: 79
url: /fa/aspose.slides.mathtext/imathgroupingcharacter/set_verticaljustification/
---
## IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) متد


هم‌ترازی عمودی کاراکتر گروه. تنظیم تراز شیء نسبت به خط پایه را مشخص می‌کند. به عنوان مثال، هنگامی که کاراکتر گروه بالای شیء قرار دارد، VerticalJustification مقدار Top به این معنی است که بالای شیء بر روی خط پایه قرار می‌گیرد؛ وقتی VerticalJustification به Bottom تنظیم شود، پایین شیء بر روی خط پایه قرار می‌گیرد پیش‌فرض: Bottom برای Position=Top و Top برای Position=Bottom

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value)=0
```

## توضیحات


مثال: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## موارد مرتبط

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* کلاس [IMathGroupingCharacter](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)