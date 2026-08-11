---
title: Add()
second_title: مرجع API Aspose.Slides برای C++
description: IMathBlock را به انتهای مجموعه اضافه می‌کند.
type: docs
weight: 14
url: /fa/aspose.slides.mathtext/imathblockcollection/add/
---
## IMathBlockCollection::Add(System::SharedPtr\<IMathBlock\>) متد

[IMathBlock](../../imathblock/) را به انتهای مجموعه اضافه می‌کند.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Add(System::SharedPtr<IMathBlock> item)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | یک بلوک ریاضی که به انتهای مجموعه اضافه می‌شود |
## توضیحات



مثال: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
```

## همچنین ببینید

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathBlock](../../imathblock/)
* کلاس [IMathBlockCollection](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)