---
title: RemoveAt()
second_title: مرجع API Aspose.Slides برای C++
description: موردی را در ایندکس مشخص شده از مجموعه حذف می‌کند.
type: docs
weight: 53
url: /fa/aspose.slides.mathtext/imathblockcollection/removeat/
---
## IMathBlockCollection::RemoveAt(int32_t) متد

یک مورد را در ایندکس مشخص شده از مجموعه حذف می‌کند.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::RemoveAt(int32_t index)=0
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | ایندکس صفر-پایهٔ موردی که باید حذف شود. |
## نکات

مثال:
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->RemoveAt(0);
```

## موارد مرتبط

* Class [IMathBlockCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)