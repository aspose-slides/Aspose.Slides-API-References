---
title: InsertClone()
second_title: مرجع API Aspose.Slides برای C++
description: یک نسخه از اسلاید چیدمان مشخص شده را در موقعیت تعیین‌شدهٔ مجموعه اضافه می‌کند.
type: docs
weight: 14
url: /fa/aspose.slides/masterlayoutslidecollection/insertclone/
---
## MasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) متد

یک نسخه از اسلاید چیدمان مشخص شده را در موقعیت تعیین‌شدهٔ مجموعه اضافه می‌کند.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | اندیس اسلاید جدید. |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) برای کلون. |

### مقدار بازگشت

اسلاید افزوده‌شده.

## توضیحات

چیدمان جدید با اسلاید اصلی والد برای این مجموعه اسلایدهای چیدمان لینک خواهد شد. بنابراین این مشابه عملیات کپی/پیست با گزینهٔ "Use Destination Theme" در PowerPoint است.

## همچنین ببینید

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ILayoutSlide](../../ilayoutslide/)
* کلاس [MasterLayoutSlideCollection](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)