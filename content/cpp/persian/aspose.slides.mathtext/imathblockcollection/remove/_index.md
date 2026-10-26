---
title: Remove()
second_title: مرجع API Aspose.Slides برای C++
description: اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند/>
type: docs
weight: 40
url: /fa/aspose.slides.mathtext/imathblockcollection/remove/
---
## IMathBlockCollection::Remove(System::SharedPtr\<IMathBlock\>) متد

اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند/>.

```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Remove(System::SharedPtr<IMathBlock> item)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | شیء‌ای که باید از مجموعه حذف شود. |

### مقدار بازگشت

true اگر *item* با موفقیت از مجموعه حذف شده باشد؛ در غیر این صورت false. این متد همچنین در صورتی که *item* در مجموعه اصلی یافت نشود false برمی‌گرداند/>.

## توضیحات


مثال:
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->Remove(block);
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathBlock](../../imathblock/)
* کلاس [IMathBlockCollection](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)