---
title: InsertClone()
second_title: مرجع API Aspose.Slides برای C++
description: یک کپی از اسلاید طرح‌بندی مشخص شده را در موقعیت تعیین‌شدهٔ مجموعه وارد می‌کند.
type: docs
weight: 14
url: /fa/aspose.slides/imasterlayoutslidecollection/insertclone/
---
## IMasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) متد


یک کپی از اسلاید طرح‌بندی مشخص‌شده را در موقعیت تعیین‌شده از مجموعه وارد می‌کند.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout)=0
```


### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | شاخص اسلاید جدید. |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) برای کلون. |

### مقدار بازگشتی

اسلاید وارد‌شده.

## توضیحات

طرح‌بندی جدید با اسلاید مستر والد برای این مجموعه اسلایدهای طرح‌بندی مرتبط خواهد شد. بنابراین این معادل عمل کپی/پیست با گزینه «Use Destination Theme» در PowerPoint است.

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ILayoutSlide](../../ilayoutslide/)
* کلاس [IMasterLayoutSlideCollection](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)