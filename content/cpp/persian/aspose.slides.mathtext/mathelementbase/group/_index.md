---
title: Group()
second_title: مرجع API Aspose.Slides برای C++
description: این عنصر را با استفاده از یک آکولاد پایین در یک گروه قرار می‌دهد
type: docs
weight: 235
url: /fa/aspose.slides.mathtext/mathelementbase/group/
---
## MathElementBase::Group() متد


این عنصر را با استفاده از یک آکولاد پایین در یک گروه قرار می‌دهد

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group() override
```

### مقدار بازگشت

نمونه جدید از نوع [IMathGroupingCharacter](../../imathgroupingcharacter/)
## توضیحات



مثال:
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## MathElementBase::Group(char16_t, MathTopBotPositions, MathTopBotPositions) متد


این عنصر را با استفاده از یک کاراکتر گروه‌بندی مانند آکولاد پایین یا کاراکتر دیگری در یک گروه قرار می‌دهد

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| character | char16_t | کاراکتر گروه‌بندی مانند آکولاد پایین (U+23DF) یا هر کاراکتر دیگری |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | موقعیت کاراکتر گروه‌بندی |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | تراز عمودی کاراکتر گروه. مکان‌یابی شیء نسبت به خط پایه را مشخص می‌کند. برای مثال، وقتی کاراکتر گروه بالای شیء باشد، VerticalJustification برابر Top نشان می‌دهد که بالای شیء بر روی خط پایه قرار دارد؛ وقتی VerticalJustification برابر Bottom تنظیم شود، پایین شیء بر روی خط پایه قرار می‌گیرد |

### مقدار بازگشت

نمونه جدید از نوع [IMathGroupingCharacter](../../imathgroupingcharacter/)
## توضیحات



مثال:
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## موارد مرتبط

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathGroupingCharacter](../../imathgroupingcharacter/)
* کلاس [MathElementBase](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)