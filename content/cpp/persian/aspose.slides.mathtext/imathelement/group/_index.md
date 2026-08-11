---
title: Group()
second_title: مرجع API Aspose.Slides برای C++
description: این عنصر را با استفاده از پرانتز کروی باز در پایین در یک گروه قرار می‌دهد
type: docs
weight: 248
url: /fa/aspose.slides.mathtext/imathelement/group/
---
## IMathElement::Group() متد

این عنصر را با استفاده از یک پرانتز کروی باز در پایین در یک گروه قرار می‌دهد

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group()=0
```

### مقدار بازگشت

نمونه جدیدی از نوع [IMathGroupingCharacter](../../imathgroupingcharacter/)
## ملاحظات

مثال:
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## IMathElement::Group(char16_t, MathTopBotPositions, MathTopBotPositions) متد

این عنصر را با استفاده از یک کاراکتر گروه‌بندی مانند پرانتز کروی باز در پایین یا هر کاراکتر دیگری در یک گروه قرار می‌دهد

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| character | char16_t | کاراکتر گروه‌بندی مانند BOTTOM CURLY BRACKET (U+23DF) یا هر کاراکتر دیگر |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | موقعیت کاراکتر گروه‌بندی |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | توجیه عمودی کاراکتر گروه. تراز شیء نسبت به baseline را مشخص می‌کند. برای مثال، وقتی کاراکتر گروه بالای شیء باشد، VerticalJustification مقدار Top نشان می‌دهد که بالای شیء بر روی baseline قرار دارد؛ وقتی VerticalJustification به Bottom تنظیم شود، پایین شیء بر روی baseline است |

### مقدار بازگشت

نمونه جدیدی از نوع [IMathGroupingCharacter](../../imathgroupingcharacter/)
## ملاحظات

مثال:
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## مراجع

* شمارش [MathTopBotPositions](../../mathtopbotpositions/)
* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathGroupingCharacter](../../imathgroupingcharacter/)
* کلاس [IMathElement](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)