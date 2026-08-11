---
title: get_Count()
second_title: مرجع API Aspose.Slides برای C++
description: تعداد عناصری که واقعاً در مجموعه موجود هستند را بر می‌گرداند. فقط قابل خواندن int32_t.
type: docs
weight: 1
url: /fa/aspose.slides.mathtext/imathblockcollection/get_count/
---
## IMathBlockCollection::get_Count() متد

تعداد عناصری که واقعاً در مجموعه موجود هستند را بر می‌گرداند. فقط-قابل-خواندن **int32_t**.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::get_Count()=0
```

## ملاحظات

مثال:
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
int32_t blocksCount = blockCollection->get_Count();
```

## موارد مرتبط

* کلاس [IMathBlockCollection](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)