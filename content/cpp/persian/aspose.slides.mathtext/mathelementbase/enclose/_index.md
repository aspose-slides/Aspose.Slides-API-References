---
title: Enclose()
second_title: Aspose.Slides برای C++ مرجع API
description: یک عنصر ریاضی را در پرانتز می‌گیرد
type: docs
weight: 27
url: /fa/aspose.slides.mathtext/mathelementbase/enclose/
---
## MathElementBase::Enclose() متد


یک عنصر ریاضی را در پرانتز می‌گیرد

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose() override
```


### مقدار بازگشت

عنصر ریاضی از نوع [IMathDelimiter](../../imathdelimiter/) که شامل پرانتز است
## توضیحات



مثال: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## MathElementBase::Enclose(char16_t, char16_t) متد


یک عنصر ریاضی را در کاراکترهای مشخص شده مانند پرانتز یا سایر کاراکترها به عنوان قاب می‌گیرد

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| beginningCharacter | char16_t | کاراکتر شروع (معمولاً کروشان سمت چپ) |
| endingCharacter | char16_t | کاراکتر پایان (معمولاً کروشان سمت راست) |

### مقدار بازگشت

عنصر ریاضی از نوع [IMathDelimiter](../../imathdelimiter/) که شامل کاراکترهای مشخص شده به عنوان قاب است
## توضیحات



مثال: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathDelimiter](../../imathdelimiter/)
* کلاس [MathElementBase](../)
* فضای نام [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)