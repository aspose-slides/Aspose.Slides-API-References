---
title: MathGroupingCharacter()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: ينشئ مثيلًا جديدًا من الفئة MathGroupingCharacter باستخدام حرف التجميع الافتراضي U+23DF (BOTTOM CURLY BRACKET)
type: docs
weight: 92
url: /ar/aspose.slides.mathtext/mathgroupingcharacter/mathgroupingcharacter/
---
## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>) constructor


ينشئ مثيلًا جديدًا من الفئة [MathGroupingCharacter](../) باستخدام حرف التجميع الافتراضي U+23DF (BOTTOM CURLY BRACKET)

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element)
```


### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | العنصر الأساسي الذي يُطبق عليه الشريط |
## ملاحظات



مثال: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
```

## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) constructor


ينشئ مثيلًا جديدًا من الفئة [MathGroupingCharacter](../).

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)
```


### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | العنصر الأساسي الذي يُطبق عليه الشريط |
| character | char16_t | حرف التجميع |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | موضع حرف التجميع |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | المحاذاة العمودية لحرف المجموعة |
## ملاحظات



مثال: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"), u'_', MathTopBotPositions::Top, MathTopBotPositions::Bottom);
```

## انظر أيضًا

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathGroupingCharacter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)