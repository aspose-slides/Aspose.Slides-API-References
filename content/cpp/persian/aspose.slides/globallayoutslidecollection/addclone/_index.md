---
title: AddClone()
second_title: Aspose.Slides برای مرجع API C++
description: یک نسخه از اسلاید چیدمان مشخص شده را به ارائه اضافه می‌کند.
type: docs
weight: 1
url: /fa/aspose.slides/globallayoutslidecollection/addclone/
---
## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) متد


یک نسخه از اسلاید چیدمان مشخص شده را به ارائه اضافه می‌کند.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) برای کلون کردن. |

### مقدار بازگشتی

اسلاید اضافه شده.
## توضیحات



هنگام کلون کردن یک چیدمان بین ارائه‌های مختلف، مستر چیدمان نیز می‌تواند برای حفظ قالب منبع کلون شود. رجیستری داخلی برای ردیابی مسترهای کلون شده به‌صورت خودکار استفاده می‌شود تا از ایجاد کلون‌های متعدد برای همان اسلاید مستر جلوگیری کند. کلون کردن دستی اسلایدهای مستر هم‌چنین جلوگیری نشده و هم‌چنین ثبت نمی‌شود. 
## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) متد


یک نسخه از اسلاید چیدمان مشخص شده را به ارائه اضافه می‌کند.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) برای کلون کردن. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | اسلاید اصلی برای یک چیدمان جدید. |

### مقدار بازگشتی

اسلاید اضافه شده.
## توضیحات



1) چیدمان جدید با مستر تعریف‌شده در ارائه مقصد لینک می‌شود. بنابراین این شبیه عملیات کپی/پیست با گزینه "Use Destination Theme" در PowerPoint است. 2) معادل این متد، متد [IMasterLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../imasterlayoutslidecollection/addclone/) است که از طریق ویژگی [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/) قابل دسترسی است. 
## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [ILayoutSlide](../../ilayoutslide/)
* کلاس [GlobalLayoutSlideCollection](../)
* کلاس [IMasterSlide](../../imasterslide/)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)