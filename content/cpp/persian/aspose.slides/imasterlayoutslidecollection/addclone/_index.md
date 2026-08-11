---
title: AddClone()
second_title: مرجع API Aspose.Slides برای C++
description: یک نسخه از اسلاید طرح‌بندی مشخص شده را به انتهای مجموعه اضافه می‌کند.
type: docs
weight: 1
url: /fa/aspose.slides/imasterlayoutslidecollection/addclone/
---
## IMasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) متد

یک نسخه از اسلاید طرح‌بندی مشخص شده را به انتهای مجموعه اضافه می‌کند.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) برای کلون کردن. |

### مقدار برگشتی

اسلاید افزوده شد.

## ملاحظات

1) طرح‌بندی جدید با اسلاید اصلی پدر برای این مجموعه اسلایدهای طرح‌بندی ارتباط خواهد یافت. بنابراین این مشابه عمل کپی/پیست با گزینه "Use Destination Theme" در PowerPoint است. 2) مشابه این متد، متد [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) است که با ویژگی [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/) دسترسی می‌یابد. 
## مراجع

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ILayoutSlide](../../ilayoutslide/)
* کلاس [IMasterLayoutSlideCollection](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)