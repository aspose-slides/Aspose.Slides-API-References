---
title: CreateMathAccent()
second_title: Aspose.Slides برای مرجع API C++
description: یک لهجه ریاضی ایجاد می‌کند که بر روی عنصر ریاضی مشخص با مقدار پیش‌فرض کاراکتر لهجه اعمال می‌شود
type: docs
weight: 1
url: /fa/aspose.slides.mathtext/imathaccentfactory/createmathaccent/
---
## IMathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>) متد

یک لهجه ریاضی ایجاد می‌کند که بر روی یک عنصر ریاضی مشخص با مقدار پیش‌فرض کاراکتر لهجه اعمال می‌شود

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصر ریاضی برای اعمال لهجه |

### مقدار بازگشت

لهجه ریاضی جدید

## IMathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>, char16_t) متد

یک لهجه ریاضی ایجاد می‌کند که بر روی یک عنصر ریاضی مشخص اعمال می‌شود

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصر ریاضی برای اعمال لهجه |
| accentCharacter | char16_t | کاراکتر لهجه |

### مقدار بازگشت

لهجه ریاضی جدید

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathAccent](../../imathaccent/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [IMathAccentFactory](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)