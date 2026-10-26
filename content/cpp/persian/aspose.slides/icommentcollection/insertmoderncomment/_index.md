---
title: InsertModernComment()
second_title: Aspose.Slides برای C++ مستندات API
description: نظر مدرن جدیدی را به مجموعه‌ای در اندیس مشخص‌شده وارد می‌کند.
type: docs
weight: 53
url: /fa/aspose.slides/icommentcollection/insertmoderncomment/
---
## ICommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) متد

یک نظر مدرن جدید را به مجموعه‌ای در ایندکس مشخص‌شده اضافه می‌کند.

```cpp
virtual System::SharedPtr<IModernComment> Aspose::Slides::ICommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | اندیس عنصری در مجموعه که نظر مدرن باید در آن درج شود. |
| text | [System::String](../../../system/string/) | متن ساده‌ی یک نظر مدرن جدید. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) در ارائه‌ای که می‌خواهید یک نظر مدرن جدید اضافه کنید. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) بر روی اسلایدی که نظر مدرن جدید به آن مرتبط است. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | موقعیت بر روی اسلایدی که می‌خواهید نظر مدرن جدید را اضافه کنید. |
| creationTime | [System::DateTime](../../../system/datetime/) | زمان ایجاد یک نظر مدرن. |

### مقدار بازگشت

نظر مدرن درج‌شده.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IModernComment](../../imoderncomment/)
* کلاس [String](../../../system/string/)
* کلاس [ISlide](../../islide/)
* کلاس [IShape](../../ishape/)
* کلاس [PointF](../../../system.drawing/pointf/)
* کلاس [DateTime](../../../system/datetime/)
* کلاس [ICommentCollection](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)