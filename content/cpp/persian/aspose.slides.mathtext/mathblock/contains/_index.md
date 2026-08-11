---
title: Contains()
second_title: مرجع API Aspose.Slides برای C++
description: تعیین می‌کند که آیا مجموعه شامل مقدار خاصی است یا خیر.
type: docs
weight: 105
url: /fa/aspose.slides.mathtext/mathblock/contains/
---
## MathBlock::Contains(System::SharedPtr\<IMathElement\>) متد

تعیین می‌کند که آیا مجموعه شامل مقدار خاصی است یا نه.

```cpp
bool Aspose::Slides::MathText::MathBlock::Contains(System::SharedPtr<IMathElement> item) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | شیئی که باید در مجموعه پیدا شود. |

## مقدار بازگشت

در صورتی که *item* در مجموعه یافت شود، true؛ در غیر این صورت، false.

## مراجع

مثال: ```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
bool contains = mathBlock->Contains(plusElement);
```

## همچنین ببینید

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathBlock](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)