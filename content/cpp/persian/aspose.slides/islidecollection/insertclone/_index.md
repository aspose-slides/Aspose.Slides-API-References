---
title: InsertClone()
second_title: Aspose.Slides برای مرجع API C++
description: یک نسخه از اسلاید مشخص‌شده را در موقعیت تعیین‌شده از مجموعه وارد می‌کند.
type: docs
weight: 27
url: /fa/aspose.slides/islidecollection/insertclone/
---
## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) متد

یک کپی از اسلاید مشخص شده را در موقعیت تعیین‌شده از مجموعه وارد می‌کند.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide)=0
```

### پارامترها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| index | **int32_t** | اندیس اسلاید جدید. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) برای کلون کردن. |

### مقدار بازگشتی

اسلاید وارد شده.

## نکات

هنگام کلون یک اسلاید بین ارائه‌های مختلف، مستر اسلاید نیز می‌تواند کلون شود. رجیستری داخلی برای ردیابی مسترهای کلون‌شده به‌صورت خودکار استفاده می‌شود تا از ایجاد چندین کلون از همان مستر اسلاید جلوگیری کند. کلون دستی مستر اسلایدها نه جلوگیری می‌شود و نه ثبت می‌شود. اگر به کنترل بیشتری بر فرآیند کلون نیاز دارید، از [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) یا [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./) برای کلون اسلایدها و [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) برای کلون مسترها استفاده کنید.

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) متد

یک کپی از اسلاید مشخص شده را در موقعیت تعیین‌شده از مجموعه وارد می‌کند.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```

### پارامترها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| index | **int32_t** | اندیس اسلاید جدید. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) برای کلون کردن. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | اسلاید چیدمان برای اسلاید جدید. |

### مقدار بازگشتی

اسلاید وارد شده.

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) متد

یک کپی از اسلاید منبع مشخص شده را در موقعیت تعیین‌شده از مجموعه وارد می‌کند. چیدمان مناسب به‌صورت خودکار از مستر مشخص شده انتخاب می‌شود (چیدمان مناسب همانچیزی است که نوع یا نامش با چیدمان اسلاید منبع یکسان باشد). اگر چیدمان مناسب وجود نداشته باشد، چیدمان اسلاید منبع کلون می‌شود (اگر allowCloneMissingLayout برابر true باشد) یا PptxEditException پرتاب می‌شود (اگر allowCloneMissingLayout برابر false باشد).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```

### پارامترها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| index | **int32_t** | اندیس اسلاید جدید. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) برای کلون کردن. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | مستر اسلاید برای اسلاید جدید. |
| allowCloneMissingLayout | **bool** | اگر در مستر مشخص شده چیدمان مناسب وجود نداشته باشد، چیدمان اسلاید منبع کلون می‌شود (اگر allowCloneMissingLayout برابر true باشد) یا PptxEditException پرتاب می‌شود (اگر allowCloneMissingLayout برابر false باشد). |

### مقدار بازگشتی

اسلاید وارد شده.

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [ISlideCollection](../)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)