---
title: CreateMathAccent()
second_title: مرجع API Aspose.Slides برای C++
description: یک لهجه ریاضی می‌سازد که به یک عنصر ریاضی مشخص اعمال می‌شود با مقدار پیش‌فرض کاراکتر لهجه
type: docs
weight: 1
url: /fa/aspose.slides.mathtext/mathaccentfactory/createmathaccent/
---
## MathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>) متد

یک لهجه ریاضی ایجاد می‌کند که به یک عنصر ریاضی مشخص اعمال می‌شود با مقدار پیش‌فرض کاراکتر لهجه

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصر ریاضی برای اعمال لهجه |

### مقدار بازگشت

لهجه ریاضی جدید

## MathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>, char16_t) متد

یک لهجه ریاضی ایجاد می‌کند که به یک عنصر ریاضی مشخص اعمال می‌شود

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصر ریاضی برای اعمال لهجه |
| accentCharacter | char16_t | کاراکتر لهجه |

### مقدار بازگشت

لهجه ریاضی جدید

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathAccent](../../imathaccent/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathAccentFactory](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)