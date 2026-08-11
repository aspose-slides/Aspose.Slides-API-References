---
title: Enclose()
second_title: مرجع API Aspose.Slides برای C++
description: یک عنصر ریاضی را در کاراکترهای مشخص شده مانند پرانتز یا سایر کاراکترها به عنوان قاب می‌پوشاند
type: docs
weight: 170
url: /fa/aspose.slides.mathtext/mathdelimiter/enclose/
---
## MathDelimiter::Enclose(char16_t, char16_t) متد

یک عنصر ریاضی را در کاراکترهای مشخص شده مانند پرانتز یا سایر کاراکترها به عنوان قاب می‌پوشاند

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathDelimiter::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| beginningCharacter | char16_t | کاراکتر آغاز (معمولاً کروشهٔ چپ) |
| endingCharacter | char16_t | کاراکتر پایان (معمولاً کروشهٔ راست) |

### مقدار بازگشتی

اگر *beginningCharacter* و *endingCharacter* خالی باشند، خصوصیات مربوطه فقط مقداردهی می‌شوند و شی جدیدی ساخته نمی‌شود (این نمونه بازگردانده می‌شود). در غیر این صورت، یک عنصر ریاضی جدید از نوع Delimiter که کاراکترهای مشخص شده را به صورت قاب شامل می‌شود و این نمونهٔ [MathDelimiter](../) داخل آن قاب‌بندی می‌شود، بازگردانده می‌شود.

## نکات

مثال:
```cpp
auto innerDelimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u",y"))->Enclose(u'{', u'}');
auto outerDelimiter = innerDelimiter->Enclose(u'[', u']');
```

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathDelimiter](../../imathdelimiter/)
* Class [MathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)