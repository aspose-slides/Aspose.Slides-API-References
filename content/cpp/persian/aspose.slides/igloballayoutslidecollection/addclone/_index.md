---
title: AddClone()
second_title: مرجع API Aspose.Slides برای C++
description: یک نسخه از اسلاید طرح مشخص شده را به ارائه اضافه می‌کند.
type: docs
weight: 1
url: /fa/aspose.slides/igloballayoutslidecollection/addclone/
---
## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) متد

یک کپی از اسلاید طرح مشخص شده را به ارائه اضافه می‌کند.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) برای کلون کردن. |

### مقدار بازگشت

اسلاید اضافه شده.

## یادداشت‌ها

هنگام کلون کردن یک طرح بین ارائه‌های مختلف، مستر طرح نیز می‌تواند کلون شود تا قالب‌بندی منبع حفظ شود. یک رجیستری داخلی برای ردیابی مسترهای کلون شده به‌صورت خودکار استفاده می‌شود تا از ایجاد چندین کلون از یک اسلاید مستر جلوگیری شود. کلون کردن دستی اسلایدهای مستر هم جلوگیری نمی‌شود و هم ثبت نمی‌گردد.

## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) متد

یک کپی از اسلاید طرح مشخص شده را به ارائه اضافه می‌کند.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) برای کلون کردن. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | اسلاید مستر برای یک طرح جدید. |

### مقدار بازگشت

اسلاید اضافه شده.

## یادداشت‌ها

طرح جدید با مستر تعریف‌شده در ارائه مقصد لینک خواهد شد. بنابراین این معادل عملیات copy/paste با گزینه "Use Destination Theme" در PowerPoint است.

## مراجع

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ILayoutSlide](../../ilayoutslide/)
* کلاس [IGlobalLayoutSlideCollection](../)
* کلاس [IMasterSlide](../../imasterslide/)
* فضازمان [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)