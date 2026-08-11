---
title: InsertComment()
second_title: مرجع API Aspose.Slides برای C++
description: یک نظر جدید را در مجموعه‌ای در اندیس مشخص شده درج کنید.
type: docs
weight: 40
url: /fa/aspose.slides/icommentcollection/insertcomment/
---
## ICommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) متد

یک نظر جدید را در مجموعه‌ای در اندیس مشخص شده درج کنید.

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس عنصری در یک مجموعه که در آن نظر باید درج شود. |
| text | [System::String](../../../system/string/) | متن ساده یک نظر جدید. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) در یک ارائه که در آن نظر جدید اضافه می‌شود. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | موقعیت روی یک اسلاید که در آن نظر جدید اضافه می‌شود. |
| creationTime | [System::DateTime](../../../system/datetime/) | زمان ایجاد یک نظر. |

### مقدار بازگشتی

نظر درج شده.

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IComment](../../icomment/)
* کلاس [String](../../../system/string/)
* کلاس [ISlide](../../islide/)
* کلاس [PointF](../../../system.drawing/pointf/)
* کلاس [DateTime](../../../system/datetime/)
* کلاس [ICommentCollection](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)