---
title: AddComment()
second_title: Aspose.Slides برای C++ مرجع API
description: یک نظر جدید را در انتهای یک مجموعه اضافه می‌کند.
type: docs
weight: 53
url: /fa/aspose.slides/commentcollection/addcomment/
---
## CommentCollection::AddComment(System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) متد

یک نظر جدید را در انتهای یک مجموعه اضافه می‌کند.

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::AddComment(System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | متن ساده یک نظر جدید. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) در یک ارائه که می‌خواهید یک نظر جدید اضافه کنید. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | موقعیت روی اسلایدی که می‌خواهید یک نظر جدید اضافه کنید. |
| creationTime | [System::DateTime](../../../system/datetime/) | زمان ایجاد یک نظر. |

## مقدار بازگشتی

نظر اضافه شده.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IComment](../../icomment/)
* کلاس [String](../../../system/string/)
* کلاس [ISlide](../../islide/)
* کلاس [PointF](../../../system.drawing/pointf/)
* کلاس [DateTime](../../../system/datetime/)
* کلاس [CommentCollection](../)
* فضای نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)