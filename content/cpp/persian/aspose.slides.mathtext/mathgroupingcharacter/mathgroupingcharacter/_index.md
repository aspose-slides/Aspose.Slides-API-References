---
title: MathGroupingCharacter()
second_title: Aspose.Slides برای C++ مرجع API
description: یک نمونه جدید از کلاس MathGroupingCharacter را با کاراکتر پیش‌فرض گروه‌بندی U+23DF (BOTTOM CURLY BRACKET) مقداردهی اولیه می‌کند
type: docs
weight: 92
url: /fa/aspose.slides.mathtext/mathgroupingcharacter/mathgroupingcharacter/
---
## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>) سازنده

یک نمونه جدید از کلاس [MathGroupingCharacter](../) را با کاراکتر پیش‌فرض گروه‌بندی U+23DF (BOTTOM CURLY BRACKET) مقداردهی اولیه می‌کند.

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصری پایه که نوار بر آن اعمال می‌شود |

## توضیحات

مثال: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
```

## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) سازنده

یک نمونه جدید از کلاس [MathGroupingCharacter](../) را مقداردهی اولیه می‌کند.

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصری پایه که نوار بر آن اعمال می‌شود |
| character | char16_t | کاراکتر گروه‌بندی |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | موقعیت کاراکتر گروه‌بندی |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | ترازبندی عمودی کاراکتر گروه |

## توضیحات

مثال: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"), u'_', MathTopBotPositions::Top, MathTopBotPositions::Bottom);
```

## همچنین

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathGroupingCharacter](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)