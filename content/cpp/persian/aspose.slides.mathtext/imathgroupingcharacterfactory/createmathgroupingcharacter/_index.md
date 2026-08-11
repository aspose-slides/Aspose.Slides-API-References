---
title: CreateMathGroupingCharacter()
second_title: مرجع API Aspose.Slides برای C++
description: یک کاراکتر گروه‌بندی ریاضی ایجاد می‌کند
type: docs
weight: 1
url: /fa/aspose.slides.mathtext/imathgroupingcharacterfactory/createmathgroupingcharacter/
---
## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) متد


یک کاراکتر گروه‌بندی ریاضی ایجاد می‌کند

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصر ریاضی برای اعمال کاراکتر گروه‌بندی |
| character | char16_t | کاراکتر گروه‌بندی |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | موقعیت کاراکتر گروه‌بندی |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | تراز عمودی |

### مقدار بازگشت

new grouping character element

## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>) متد


یک کاراکتر گروه‌بندی ریاضی ایجاد می‌کند

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصر ریاضی برای اعمال کاراکتر گروه‌بندی |

### مقدار بازگشت

new grouping character element

## موارد مرتبط

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathGroupingCharacter](../../imathgroupingcharacter/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [IMathGroupingCharacterFactory](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)