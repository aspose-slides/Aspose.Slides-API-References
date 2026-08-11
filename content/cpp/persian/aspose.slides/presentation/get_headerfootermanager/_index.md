---
title: get_HeaderFooterManager()
second_title: Aspose.Slides برای C++ مرجع API
description: مدیر HeaderFooter واقعی را باز می‌گرداند. فقط خواندنی IPresentationHeaderFooterManager.
type: docs
weight: 27
url: /fa/aspose.slides/presentation/get_headerfootermanager/
---
## Presentation::get_HeaderFooterManager() متد


باز می‌گرداند مدیر HeaderFooter واقعی. فقط خواندنی [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/).

```cpp
System::SharedPtr<IPresentationHeaderFooterManager> Aspose::Slides::Presentation::get_HeaderFooterManager() override
```

## ملاحظات


مثال زیر نشان می‌دهد چگونه قابلیت مشاهدهٔ فوتر را داخل [Slide](../../slide/) در PowerPoint [Presentation](../) تنظیم کنیم.
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
auto slide = presentation->get_Slides()->idx_get(0);

System::SharedPtr<IBaseSlideHeaderFooterManager> headerFooterManager = slide->get_HeaderFooterManager();
// ویژگی IsFooterVisible برای نشان دادن عدم وجود جای‌دار فوتر اسلاید استفاده می‌شود.
if (!headerFooterManager->get_IsFooterVisible())
{
    // روش SetFooterVisibility برای قابل مشاهده کردن جای‌دار فوتر اسلاید استفاده می‌شود.
    headerFooterManager->SetFooterVisibility(true);
}

// ویژگی IsSlideNumberVisible برای نشان دادن عدم وجود جای‌دار شماره صفحه اسلاید استفاده می‌شود.
if (!headerFooterManager->get_IsSlideNumberVisible())
{
    // روش SetSlideNumberVisibility برای قابل مشاهده کردن جای‌دار شماره صفحه اسلاید استفاده می‌شود.
    headerFooterManager->SetSlideNumberVisibility(true);
}

// ویژگی IsDateTimeVisible برای نشان دادن عدم وجود جای‌دار تاریخ-زمان اسلاید استفاده می‌شود.
if (!headerFooterManager->get_IsDateTimeVisible())
{
    // روش SetFooterVisibility برای قابل مشاهده کردن جای‌دار تاریخ-زمان اسلاید استفاده می‌شود.
    headerFooterManager->SetDateTimeVisibility(true);
}

// روش SetFooterText برای تنظیم متن در جای‌دار فوتر اسلاید استفاده می‌شود.
headerFooterManager->SetFooterText(u"Footer text");
// روش SetDateTimeText برای تنظیم متن در جای‌دار تاریخ-زمان اسلاید استفاده می‌شود.
headerFooterManager->SetDateTimeText(u"Date and time text");
presentation->Save(u"Presentation.ppt", SaveFormat::Ppt);
```
 مثال زیر نشان می‌دهد چگونه قابلیت مشاهدهٔ فوتر فرزند را داخل [Slide](../../slide/) تنظیم کنیم.
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
System::SharedPtr<IMasterSlideHeaderFooterManager> headerFooterManager = presentation->get_Masters()->idx_get(0)->get_HeaderFooterManager();

// متد SetFooterAndChildFootersVisibility برای قابل مشاهده کردن اسلاید مستر و تمام جای‌دارهای فوتر فرزند استفاده می‌شود.
headerFooterManager->SetFooterAndChildFootersVisibility(true);

// متد SetSlideNumberAndChildSlideNumbersVisibility برای قابل مشاهده کردن اسلاید مستر و تمام جای‌دارهای شماره صفحه فرزند استفاده می‌شود.
headerFooterManager->SetSlideNumberAndChildSlideNumbersVisibility(true);

// متد SetDateTimeAndChildDateTimesVisibility برای قابل مشاهده کردن اسلاید مستر و تمام جای‌دارهای تاریخ-زمان فرزند استفاده می‌شود.
headerFooterManager->SetDateTimeAndChildDateTimesVisibility(true);

// متد SetFooterAndChildFootersText برای تنظیم متن در اسلاید مستر و تمام جای‌دارهای فوتر فرزند استفاده می‌شود.
headerFooterManager->SetFooterAndChildFootersText(u"Footer text");

// متد SetDateTimeAndChildDateTimesText برای تنظیم متن در اسلاید مستر و تمام جای‌دارهای تاریخ-زمان فرزند استفاده می‌شود.
headerFooterManager->SetDateTimeAndChildDateTimesText(u"Date and time text");
```

## مراجع

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/)
* کلاس [Presentation](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)