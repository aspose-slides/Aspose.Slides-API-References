---
title: get_RootDirectoryClsid()
second_title: مرجع API Aspose.Slides برای C++
description: نمایانگر GUID کلاس شیء (CLSID) است که در ورودی فهرست ریشه ذخیره می‌شود. می‌تواند برای فعال‌سازی COM برنامه‌ی سند استفاده شود. مقدار پیش‌فرض '64818D11-4F9B-11CF-86EA-00AA00B929E8' است که به 'Microsoft Powerpoint.Slide.8' مربوط می‌شود.
type: docs
weight: 1
url: /fa/aspose.slides.export/pptoptions/get_rootdirectoryclsid/
---
## PptOptions::get_RootDirectoryClsid() متد

نمایانگر GUID کلاس شیء (CLSID) است که درِ ورودی ریشهٔ فهرست ذخیره شده است. می‌تواند برای فعال‌سازی COM برنامهٔ سند استفاده شود. مقدار پیش‌فرض '64818D11-4F9B-11CF-86EA-00AA00B929E8' است که به 'Microsoft Powerpoint.Slide.8' مربوط می‌شود.

```cpp
System::Guid Aspose::Slides::Export::PptOptions::get_RootDirectoryClsid() override
```

## توضیحات

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PptOptions> pptOptions = System::MakeObject<PptOptions>();

pptOptions->set_RootDirectoryClsid(System::Guid(u"64818D10-4F9B-11CF-86EA-00AA00B929E8"));

pres->Save(u"pres.ppt", Aspose::Slides::Export::SaveFormat::Ppt, pptOptions);
```

## مراجع

* کلاس [Guid](../../../system/guid/)
* کلاس [PptOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)