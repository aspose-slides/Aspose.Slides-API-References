---
title: Delimit()
second_title: Aspose.Slides برای C++ مرجع API
description: تمام عناصر فرزند را با کاراکتر جداساز (بدون براکت) محدود می‌کند
type: docs
weight: 1
url: /fa/aspose.slides.mathtext/imathblock/delimit/
---
## متد IMathBlock::Delimit(char16_t)

تمام عناصر فرزند را با کاراکتر جداساز (بدون براکت) محدود می‌کند

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Delimit(char16_t separatorCharacter)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| separatorCharacter | char16_t | کاراکتری که به عنوان جداساز استفاده می‌شود |

### مقدار بازگشتی

نمونه‌ای از عنصر [IMathDelimiter](../../imathdelimiter/)

## توضیحات



مثال: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathDelimiter](../../imathdelimiter/)
* کلاس [IMathBlock](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)