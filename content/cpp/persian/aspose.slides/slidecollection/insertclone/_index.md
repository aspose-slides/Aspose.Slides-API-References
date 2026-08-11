---
title: InsertClone()
second_title: Aspose.Slides برای C++ مرجع API
description: یک کپی از اسلاید مشخص‌شده را در موقعیت مشخص‌شده در مجموعه درج می‌کند.
type: docs
weight: 66
url: /fa/aspose.slides/slidecollection/insertclone/
---
## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) متد

یک کپی از اسلاید مشخص‌شده را در موقعیت مشخص‌شده در مجموعه درج می‌کند.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide) override
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | ایندکس اسلاید جدید. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) برای تکثیر. |

### مقدار بازگشت

اسلاید درج‌شده.

## توضیحات

هنگام تکثیر یک اسلاید بین ارائه‌های متفاوت می‌توان مستر اسلاید را نیز تکثیر کرد. رجیستری داخلی برای ردیابی مسترهای تکثیر‌شده به‌صورت خودکار استفاده می‌شود تا از ایجاد چندین تکثیر از همان مستر اسلاید جلوگیری شود. تکثیر دستی مستر اسلایدها نه جلوگیری می‌شود و نه ثبت می‌شود. اگر به کنترل بیشتری روی فرآیند تکثیر نیاز دارید از [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/insertclone/) یا [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/insertclone/) برای تکثیر اسلایدها و [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) برای تکثیر مسترها استفاده کنید.

مثال زیر نشان می‌دهد چگونه می‌توان در موقعیت دیگری داخل [Presentation](../../presentation/) تکثیر کرد.
```cpp
// نمونه‌سازی کلاس Presentation که نمایانگر یک فایل ارائه است
auto pres = System::MakeObject<Presentation>(u"CloneWithInSamePresentation.pptx");

// تکثیر اسلاید مورد نظر به انتهای مجموعه اسلایدها در همان ارائه
System::SharedPtr<ISlideCollection> slides = pres->get_Slides();
// تکثیر اسلاید مورد نظر به ایندکس مشخص‌شده در همان ارائه
slides->InsertClone(2, slides->idx_get(1));
// نوشتن ارائهٔ تغییر یافته به دیسک
pres->Save(u"Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat::Pptx);
```
مثال زیر نشان می‌دهد چگونه می‌توان در موقعیت دیگری داخل [Presentation](../../presentation/) تکثیر کرد.
```cpp
// نمونه‌سازی کلاس Presentation برای بارگذاری فایل ارائه منبع
auto srcPres = System::MakeObject<Presentation>(u"CloneAtEndOfAnother.pptx");

// نمونه‌سازی کلاس Presentation برای فایل PPTX مقصد (جایی که اسلاید باید تکثیر شود)
auto destPres = System::MakeObject<Presentation>();

destPres->get_Slides()->InsertClone(2, srcPres->get_Slides()->idx_get(0));
// نوشتن ارائه مقصد به دیسک
destPres->Save(u"Aspose2_out.pptx", SaveFormat::Pptx);
```

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) متد

یک کپی از اسلاید مشخص‌شده را در موقعیت مشخص‌شده در مجموعه درج می‌کند.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | ایندکس اسلاید جدید. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) برای تکثیر. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Layout slide برای اسلاید جدید. |

### مقدار بازگشت

اسلاید درج‌شده.

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) متد

یک کپی از اسلاید منبع مشخص را در موقعیت مشخص‌شده در مجموعه درج می‌کند. طرح مناسب به‌صورت خودکار از مستر مشخص شده انتخاب می‌شود (طرح مناسب همان طرحی است که نوع یا نامش با طرح اسلاید منبع برابر باشد). اگر طرح مناسب وجود نداشته باشد، طرح اسلاید منبع تکثیر می‌شود (اگر allowCloneMissingLayout برابر true باشد) یا PptxEditException پرتاب می‌شود (اگر allowCloneMissingLayout برابر false باشد).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | ایندکس اسلاید جدید. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) برای تکثیر. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | مستر اسلاید برای اسلاید جدید. |
| allowCloneMissingLayout | **bool** | اگر در مستر مشخص شده طرح مناسب وجود نداشته باشد، طرح اسلاید منبع تکثیر می‌شود (اگر allowCloneMissingLayout برابر true باشد) یا PptxEditException پرتاب می‌شود (اگر allowCloneMissingLayout برابر false باشد). |

### مقدار بازگشت

اسلاید درج‌شده.

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ISlide](../../islide/)
* کلاس [SlideCollection](../)
* کلاس [ILayoutSlide](../../ilayoutslide/)
* کلاس [IMasterSlide](../../imasterslide/)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)