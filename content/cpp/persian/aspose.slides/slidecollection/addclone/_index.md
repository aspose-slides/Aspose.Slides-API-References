---
title: AddClone()
second_title: مرجع API Aspose.Slides برای C++
description: یک نسخه از اسلاید مشخص شده را به انتهای مجموعه اضافه می‌کند.
type: docs
weight: 53
url: /fa/aspose.slides/slidecollection/addclone/
---
## SlideCollection::AddClone(System::SharedPtr\<ISlide\>) method

یک نسخه از اسلاید مشخص شده را به انتهای مجموعه اضافه می‌کند.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) برای کلون کردن. |

### مقدار بازگشتی

اسلاید جدید.

## توضیحات

هنگام کلون کردن یک اسلاید بین ارائه‌های مختلف، ممکن است مستر اسلاید نیز کلون شود. یک رجیستری داخلی برای ردیابی مسترهای کلون‌شده به‌صورت خودکار استفاده می‌شود تا از ایجاد چندین کلون از همان مستر اسلاید جلوگیری شود. کلون‌کردن دستی مستر اسلایدها نه جلوگیری می‌شود و نه ثبت می‌گردد. اگر به کنترل بیشتری بر فرآیند کلون‌کردن نیاز دارید، برای کلون‌کردن اسلایدها از [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/addclone/) یا [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/addclone/)، برای کلون‌کردن چیدمان‌ها از [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) یا [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) و برای کلون‌کردن مسترها از [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) استفاده کنید. 

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) method

یک نسخه از اسلاید مشخص شده را به انتهای بخش مشخص شده اضافه می‌کند.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) برای کلون کردن. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) برای یک اسلاید جدید. |

### مقدار بازگشتی

اسلاید جدید.

## توضیحات

```cpp
auto presentation = MakeObject<Presentation>();
presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 50.0f, 300.0f, 100.0f);
presentation->get_Sections()->AddSection(u"Section 1", presentation->get_Slides()->idx_get(0));
auto section2 = presentation->get_Sections()->AppendEmptySection(u"Section 2");
presentation->get_Slides()->AddClone(presentation->get_Slides()->idx_get(0), section2);
// اکنون بخش دوم شامل یک نسخه از اسلاید اول است.
```

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) method

یک نسخه از اسلاید مشخص شده را به انتهای مجموعه اضافه می‌کند.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) برای کلون کردن. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | چیدمان اسلاید برای یک اسلاید جدید. |

### مقدار بازگشتی

اسلاید جدید.

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) method

یک نسخه از اسلاید منبع مشخص شده را به انتهای مجموعه اضافه می‌کند. چیدمان مناسب به‌صورت خودکار از مستر مشخص شده انتخاب می‌شود (چیدمان مناسب همان چیدمانی است که نوع یا نامش با چیدمان اسلاید منبع یکسان باشد). اگر چیدمان مناسب وجود نداشته باشد، چیدمان اسلاید منبع کلون می‌شود (اگر allowCloneMissingLayout برابر true باشد) یا PptxEditException پرتاب می‌شود (اگر allowCloneMissingLayout برابر false باشد).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) برای کلون کردن. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | مستر اسلاید برای یک اسلاید جدید. |
| allowCloneMissingLayout | **bool** | اگر در مستر مشخص شده هیچ چیدمان مناسبی وجود نداشته باشد، چیدمان اسلاید منبع کلون خواهد شد (اگر allowCloneMissingLayout برابر true باشد) یا PptxEditException پرتاب می‌شود (اگر allowCloneMissingLayout برابر false باشد). |

### مقدار بازگشتی

اسلاید جدید.

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ISlide](../../islide/)
* کلاس [SlideCollection](../)
* کلاس [ISection](../../isection/)
* کلاس [ILayoutSlide](../../ilayoutslide/)
* کلاس [IMasterSlide](../../imasterslide/)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)