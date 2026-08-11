---
title: InsertClone()
second_title: مرجع API Aspose.Slides برای C++
description: یک کپی از اسلاید مستر مشخص شده را در موقعیت تعیین‌شده از مجموعه وارد می‌کند. اسلایدهای طرح‌بندی پیوسته نیز کپی می‌شوند.
type: docs
weight: 105
url: /fa/aspose.slides/masterslidecollection/insertclone/
---
## MasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) متد

یک کپی از اسلاید مستر مشخص شده را در موقعیت مشخص شده از مجموعه وارد می‌کند. اسلایدهای طرح‌بندی پیوندی نیز کپی می‌شوند.

```cpp
System::SharedPtr<IMasterSlide> Aspose::Slides::MasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster) override
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | اندیس اسلاید جدید. |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) برای کلون کردن. |

### مقدار بازگشت

اسلاید مستر وارد شده.

## ملاحظات

مثال زیر نشان می‌دهد چگونه می‌توان اسلاید مستر را در یک PowerPoint دیگر [Presentation](../../presentation/) کلون کرد.
```cpp
// یک شی از کلاس Presentation ایجاد می‌کند تا فایل ارائه منبع را بارگذاری کند
auto srcPres = System::MakeObject<Presentation>(u"CloneToAnotherPresentationWithMaster.pptx");

// یک شی از کلاس Presentation برای ارائه مقصد ایجاد می‌کند (جایی که اسلاید باید کلون شود)
auto destPres = System::MakeObject<Presentation>();

// یک شی از ISlide را از مجموعه اسلایدها در ارائه منبع به همراه
// اسلاید مستر
auto sourceSlide = srcPres->get_Slides()->idx_get(0);
auto sourceMaster = sourceSlide->get_LayoutSlide()->get_MasterSlide();
// دریافت اسلایدهای مستر از ارائه مقصد
auto masters = destPres->get_Masters();
// کلون کردن اسلاید مستر موردنظر از ارائه منبع به مجموعه مسترهای
// ارائه مقصد
System::SharedPtr<IMasterSlide> iSlide = masters->AddClone(sourceMaster);
// مجموعه اسلایدها در ارائه مقصد
auto slides = destPres->get_Slides();
// کلون کردن اسلاید منبع به مجموعه اسلایدهای مقصد.
slides->AddClone(sourceSlide, iSlide, true);
// ذخیرهٔ ارائه مقصد بر روی دیسک
destPres->Save(u"CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat::Pptx);
```

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMasterSlide](../../imasterslide/)
* Class [MasterSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)