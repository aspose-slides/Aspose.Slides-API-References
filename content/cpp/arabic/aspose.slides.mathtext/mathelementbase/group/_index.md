---
title: Group()
second_title: مرجع API Aspose.Slides للغة C++
description: يوضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي
type: docs
weight: 235
url: /ar/aspose.slides.mathtext/mathelementbase/group/
---
## MathElementBase::Group() method

يوضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group() override
```

### قيمة الإرجاع

مثال جديد من النوع [IMathGroupingCharacter](../../imathgroupingcharacter/)
## ملاحظات

مثال: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## MathElementBase::Group(char16_t, MathTopBotPositions, MathTopBotPositions) method

يوضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| الحرف | char16_t | حرف تجميع مثل القوس المعقوف السفلي (U+23DF) أو أي حرف آخر |
| الموضع | [MathTopBotPositions](../../mathtopbotpositions/) | موضع حرف التجميع |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | المبرر الرأسي لحرف المجموعة. يحدد محاذاة الكائن بالنسبة إلى خط القاعدة. على سبيل المثال، عندما يكون حرف المجموعة فوق الكائن، فإن VerticalJustification ذات القيمة Top يشير إلى أن أعلى الكائن يقع على خط القاعدة؛ عندما يتم تعيين VerticalJustification إلى Bottom، يكون أسفل الكائن على خط القاعدة |

### قيمة الإرجاع

مثال جديد من النوع [IMathGroupingCharacter](../../imathgroupingcharacter/)
## ملاحظات

مثال: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## انظر أيضًا

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Class [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)