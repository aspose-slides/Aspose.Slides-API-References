---
title: InsertComment()
second_title: Aspose.Slides برای مرجع API C++
description: یک کامنت جدید را در یک مجموعه در ایندکس مشخص شده درج کنید.
type: docs
weight: 79
url: /fa/aspose.slides/commentcollection/insertcomment/
---
## CommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) متد


یک کامنت جدید را در یک مجموعه در ایندکس مشخص شده درج می‌کند.

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| index | **int32_t** | شاخص عنصری در یک مجموعه که کامنت باید در آن درج شود. |
| text | [System::String](../../../system/string/) | متن ساده یک کامنت جدید. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) در یک ارائه که برای اضافه کردن یک کامنت جدید. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | موقعیت روی یک اسلاید که برای اضافه کردن یک کامنت جدید. |
| creationTime | [System::DateTime](../../../system/datetime/) | زمان ایجاد یک کامنت. |

### مقدار برگشتی

کامنت درج‌شده.

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IComment](../../icomment/)
* کلاس [String](../../../system/string/)
* کلاس [ISlide](../../islide/)
* کلاس [PointF](../../../system.drawing/pointf/)
* کلاس [DateTime](../../../system/datetime/)
* کلاس [CommentCollection](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)