---
title: CreateMathGroupingCharacter()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ حرف تجميع رياضي
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/imathgroupingcharacterfactory/createmathgroupingcharacter/
---
## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) طريقة

ينشئ حرف تجميع رياضي

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```


### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصر رياضي لتطبيق حرف التجميع |
| character | char16_t | حرف التجميع |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | موضع حرف التجميع |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | محاذاة عمودية |

### قيمة الإرجاع

عنصر تجميع رياضي جديد

## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>) طريقة


ينشئ حرف تجميع رياضي

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element)=0
```


### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصر رياضي لتطبيق حرف التجميع |

### قيمة الإرجاع

عنصر تجميع رياضي جديد

## أنظر أيضًا

* تعداد [MathTopBotPositions](../../mathtopbotpositions/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathGroupingCharacter](../../imathgroupingcharacter/)
* فئة [IMathElement](../../imathelement/)
* فئة [IMathGroupingCharacterFactory](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)