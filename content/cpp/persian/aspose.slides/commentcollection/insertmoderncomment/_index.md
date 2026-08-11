---
title: InsertModernComment()
second_title: مرجع API Aspose.Slides برای C++
description: یک نظر مدرن جدید را به مجموعه‌ای در ایندکس مشخص‌شده درج می‌کند.
type: docs
weight: 92
url: /fa/aspose.slides/commentcollection/insertmoderncomment/
---
## CommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) متد

یک نظر مدرن جدید را به مجموعه‌ای در ایندکس مشخص شده درج می‌کند.

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس عنصری در یک مجموعه که نظر مدرن باید در آن درج شود. |
| text | [System::String](../../../system/string/) | متن ساده یک نظر مدرن جدید. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) در یک ارائه که نظر مدرن جدید به آن اضافه می‌شود. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) بر روی اسلایدی که یک نظر مدرن جدید به آن مرتبط است. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | موقعیت بر روی اسلایدی که نظر مدرن جدید به آن اضافه می‌شود. |
| creationTime | [System::DateTime](../../../system/datetime/) | زمان ایجاد یک نظر مدرن. |

### مقدار بازگشت

نظر مدرن درج شده.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IModernComment](../../imoderncomment/)
* کلاس [String](../../../system/string/)
* کلاس [ISlide](../../islide/)
* کلاس [IShape](../../ishape/)
* کلاس [PointF](../../../system.drawing/pointf/)
* کلاس [DateTime](../../../system/datetime/)
* کلاس [CommentCollection](../)
* فضای نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)