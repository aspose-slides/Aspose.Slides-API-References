---
title: AddComment()
second_title: Aspose.Slides برای C++ - مرجع API
description: یک نظر جدید را در انتهای یک مجموعه اضافه می‌کند.
type: docs
weight: 14
url: /fa/aspose.slides/icommentcollection/addcomment/
---
## ICommentCollection::AddComment(System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) متد

یک نظر جدید در انتهای یک مجموعه اضافه می‌کند.

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::AddComment(System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | متن سادهٔ یک نظر جدید. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) در یک ارائه که می‌خواهید نظر جدیدی اضافه کنید. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | موقعیت روی اسلایدی که می‌خواهید نظر جدیدی اضافه کنید. |
| creationTime | [System::DateTime](../../../system/datetime/) | زمان ایجاد یک نظر. |

### مقدار بازگشت

نظر اضافه شده.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IComment](../../icomment/)
* کلاس [String](../../../system/string/)
* کلاس [ISlide](../../islide/)
* کلاس [PointF](../../../system.drawing/pointf/)
* کلاس [DateTime](../../../system/datetime/)
* کلاس [ICommentCollection](../)
* فضای‌نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)