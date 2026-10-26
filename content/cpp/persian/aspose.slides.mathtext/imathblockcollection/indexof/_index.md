---
title: IndexOf()
second_title: Aspose.Slides برای C++ مرجع API
description: اندیس یک IMathBlock خاص را در مجموعه تعیین می‌کند.
type: docs
weight: 79
url: /fa/aspose.slides.mathtext/imathblockcollection/indexof/
---
## IMathBlockCollection::IndexOf(System::SharedPtr\<IMathBlock\>) متد

اندیس یک [IMathBlock](../../imathblock/) خاص را در مجموعه تعیین می‌کند.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::IndexOf(System::SharedPtr<IMathBlock> item)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | آیتمی که باید در مجموعه پیدا شود. |

### مقدار بازگشت

اندیس *item* اگر در مجموعه یافت شود؛ در غیر اینصورت، -1.

## توضیحات



مثال: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
int32_t index = blockCollection->IndexOf(block);
```

## مراجع

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathBlock](../../imathblock/)
* کلاس [IMathBlockCollection](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)