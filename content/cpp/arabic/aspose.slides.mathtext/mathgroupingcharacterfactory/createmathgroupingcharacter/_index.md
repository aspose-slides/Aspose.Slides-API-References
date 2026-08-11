---
title: CreateMathGroupingCharacter()
second_title: Aspose.Slides للغة C++ مرجع API
description: ينشئ حرف تجميع رياضي
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/mathgroupingcharacterfactory/createmathgroupingcharacter/
---
## MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) طريقة

ينشئ حرف تجميع رياضي

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | العنصر الرياضي لتطبيق حرف التجميع |
| character | char16_t | حرف التجميع |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | موضع حرف التجميع |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | المحاذاة العمودية |

### قيمة الإرجاع

عنصر حرف التجميع الجديد

## MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>) طريقة

ينشئ حرف تجميع رياضي

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | العنصر الرياضي لتطبيق حرف التجميع |

### قيمة الإرجاع

عنصر حرف التجميع الجديد

## انظر أيضًا

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Class [IMathElement](../../imathelement/)
* Class [MathGroupingCharacterFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)