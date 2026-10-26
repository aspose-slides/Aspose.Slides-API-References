---
title: Enclose()
second_title: مرجع API Aspose.Slides برای C++
description: عنصر ریاضی را در پرانتز می‌گیرد
type: docs
weight: 40
url: /fa/aspose.slides.mathtext/imathelement/enclose/
---
## IMathElement::Enclose() متد

عنصر ریاضی را در پرانتز می‌گیرد

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose()=0
```

### مقدار بازگشت

عنصر ریاضی از نوع [IMathDelimiter](../../imathdelimiter/) که پرانتز را شامل می‌شود
## توضیحات



مثال: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## IMathElement::Enclose(char16_t, char16_t) متد

این عنصر را در کاراکترهای مشخصی مانند پرانتز یا سایر کاراکترها به عنوان چارچوب می‌گیرد

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose(char16_t beginningCharacter, char16_t endingCharacter)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| beginningCharacter | char16_t | کاراکتر آغاز (معمولاً پرانتز چپ) |
| endingCharacter | char16_t | کاراکتر پایان (معمولاً پرانتز راست) |

### مقدار بازگشت

عنصر ریاضی از نوع [IMathDelimiter](../../imathdelimiter/) که کاراکترهای مشخص شده را به عنوان چارچوب شامل می‌شود
## توضیحات



مثال: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## همچنین ببینید

* نوع‌تعریف [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathDelimiter](../../imathdelimiter/)
* کلاس [IMathElement](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)