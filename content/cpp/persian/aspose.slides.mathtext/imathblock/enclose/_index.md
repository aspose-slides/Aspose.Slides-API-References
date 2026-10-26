---
title: Enclose()
second_title: Aspose.Slides برای C++ مرجع API
description: عناصر فرزند این بلوک را با کاراکترهای مشخص‌شده مانند پرانتز یا سایر به عنوان قاب محصور می‌کند و با کاراکتر جداکننده تفکیک می‌نماید
type: docs
weight: 14
url: /fa/aspose.slides.mathtext/imathblock/enclose/
---
## IMathBlock::Enclose(char16_t, char16_t, char16_t) متد


عناصر فرزند این بلوک را با کاراکترهای مشخص‌شده مانند پرانتز یا سایر به عنوان قاب محصور می‌کند و با یک کاراکتر جداکننده delimit می‌کند

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| beginningCharacter | char16_t | کاراکتر آغاز (معمولاً پرانتز چپ) |
| endingCharacter | char16_t | کاراکتر پایان (معمولاً پرانتز راست) |
| separatorCharacter | char16_t | کاراکتر جداکننده |

### مقدار بازگشتی

عنصر ریاضی از نوع [IMathDelimiter](../../imathdelimiter/) که کاراکترهای مشخص‌شده را به عنوان قاب و جداکننده شامل می‌شود
## توضیحات



مثال: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## همچنین ببینید

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathDelimiter](../../imathdelimiter/)
* کلاس [IMathBlock](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)