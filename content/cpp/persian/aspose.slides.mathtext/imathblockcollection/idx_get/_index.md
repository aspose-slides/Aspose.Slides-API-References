---
title: idx_get()
second_title: مرجع API Aspose.Slides برای C++
description: مورد را در اندیس مشخص‌شده دریافت می‌کند. فقط خواندنی IMathBlock.
type: docs
weight: 92
url: /fa/aspose.slides.mathtext/imathblockcollection/idx_get/
---
## IMathBlockCollection::idx_get(int32_t) متد

مورد را در اندیس مشخص‌شده دریافت می‌کند. فقط خواندنی [IMathBlock](../../imathblock/).

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockCollection::idx_get(int32_t index)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس صفر-پایه‌ای مورد برای دریافت |

### مقدار بازگشتی

بلوک متن ریاضی.

## توضیحات

مثال:
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
auto block = blockCollection->idx_get(1);
```

## مراجع

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathBlock](../../imathblock/)
* کلاس [IMathBlockCollection](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)