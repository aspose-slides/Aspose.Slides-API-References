---
title: Group()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي
type: docs
weight: 248
url: /ar/aspose.slides.mathtext/imathelement/group/
---
## IMathElement::Group() طريقة


يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group()=0
```


### قيمة الإرجاع

مثيل جديد من النوع [IMathGroupingCharacter](../../imathgroupingcharacter/)
## ملاحظات



مثال: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## IMathElement::Group(char16_t, MathTopBotPositions, MathTopBotPositions) طريقة


يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل قوس معقوف سفلي أو غيره

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```


### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| character | char16_t | حرف تجميع مثل BOTTOM CURLY BRACKET (U+23DF) أو أي آخر |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | موضع حرف التجميع |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | محاذاة عمودية لحرف المجموعة. يحدد محاذاة الكائن بالنسبة إلى خط القاعدة. على سبيل المثال، عندما يكون حرف المجموعة فوق الكائن، فإن VerticalJustification من Top يعني أن أعلى الكائن يقع على خط القاعدة؛ وعند تعيين VerticalJustification إلى Bottom، يكون أسفل الكائن على خط القاعدة |

### قيمة الإرجاع

مثيل جديد من النوع [IMathGroupingCharacter](../../imathgroupingcharacter/)
## ملاحظات



مثال: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## انظر أيضًا

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IMathGroupingCharacter](../../imathgroupingcharacter/)
* فئة [IMathElement](../)
* نطاق [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)