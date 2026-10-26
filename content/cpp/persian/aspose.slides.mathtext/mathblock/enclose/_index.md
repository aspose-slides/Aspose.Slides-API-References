---
title: Enclose()
second_title: مرجع API Aspose.Slides برای C++
description: عناصر فرزند این بلوک را در کاراکترهای مشخص شده مانند پرانتز یا سایر کاراکترها به عنوان قاب می‌گیرد
type: docs
weight: 222
url: /fa/aspose.slides.mathtext/mathblock/enclose/
---
## MathBlock::Enclose(char16_t, char16_t) متد


عناصر فرزند این بلوک را در کاراکترهای مشخص شده مانند پرانتز یا سایر کاراکترها به عنوان قاب می‌گیرد

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| beginningCharacter | char16_t | کاراکتر آغاز (معمولاً پرانتز چپ) |
| endingCharacter | char16_t | کاراکتر پایان (معمولاً پرانتز راست) |

### مقدار بازگردانده شده

عنصر ریاضی از نوع [IMathDelimiter](../../imathdelimiter/) که کاراکترهای مشخص شده را به عنوان قاب شامل می‌شود
## توضیحات



مثال:
```cpp
auto block = System::MakeObject<MathematicalText>(u"x")->Join(u"+y");
auto delimiter = System::ExplicitCast<IMathElement>(block)->Enclose(u'[', u']');
```

## MathBlock::Enclose(char16_t, char16_t, char16_t) متد


عناصر فرزند این بلوک را در کاراکترهای مشخص شده مانند پرانتز یا سایر کاراکترها به عنوان قاب می‌گیرد و با یک کاراکتر جداکننده جداسازی می‌کند

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| beginningCharacter | char16_t | کاراکتر آغاز (معمولاً پرانتز چپ) |
| endingCharacter | char16_t | کاراکتر پایان (معمولاً پرانتز راست) |
| separatorCharacter | char16_t | کاراکتر جداکننده |

### مقدار بازگردانده شده

عنصر ریاضی از نوع [IMathDelimiter](../../imathdelimiter/) که کاراکترهای مشخص شده را به عنوان قاب و جداکننده شامل می‌شود
## توضیحات



مثال:
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathDelimiter](../../imathdelimiter/)
* کلاس [MathBlock](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)