---
title: Delimit()
second_title: مرجع API Aspose.Slides برای C++
description: عناصر فرزند را با کاراکتر جداکننده محدود می‌کند (بدون براکت‌ها)
type: docs
weight: 209
url: /fa/aspose.slides.mathtext/mathblock/delimit/
---
## MathBlock::Delimit(char16_t) متد

عناصر فرزند را با کاراکتر جداکننده محدود می‌کند (بدون براکت‌ها)

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Delimit(char16_t separatorCharacter) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| separatorCharacter | char16_t | کاراکتر جداکننده |

### مقدار بازگشت

عنصر ریاضی از نوع [IMathDelimiter](../../imathdelimiter/)
## توضیحات



مثال: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## مطالب مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathDelimiter](../../imathdelimiter/)
* کلاس [MathBlock](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)