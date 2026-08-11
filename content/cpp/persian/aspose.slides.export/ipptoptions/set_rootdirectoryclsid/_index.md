---
title: set_RootDirectoryClsid()
second_title: "مرجع API Aspose.Slides برای C++"
description: "نمایش‌دهنده GUID کلاس شیء (CLSID) که در ورودی ریشه‌دایرکتوری ذخیره می‌شود. می‌تواند برای فعال‌سازی COM برنامه سند استفاده شود. مقدار پیش‌فرض '64818D11-4F9B-11CF-86EA-00AA00B929E8' است که به 'Microsoft Powerpoint.Slide.8' مربوط می‌شود."
type: docs
weight: 14
url: /fa/aspose.slides.export/ipptoptions/set_rootdirectoryclsid/
---
## IPptOptions::set_RootDirectoryClsid(System::Guid) متد

نمایش‌دهنده GUID کلاس شیء (CLSID) که در ورودی ریشه‌دایرکتوری ذخیره می‌شود. می‌تواند برای فعال‌سازی COM برنامه سند استفاده شود. مقدار پیش‌فرض '64818D11-4F9B-11CF-86EA-00AA00B929E8' است که به 'Microsoft Powerpoint.Slide.8' مربوط می‌شود.

```cpp
virtual void Aspose::Slides::Export::IPptOptions::set_RootDirectoryClsid(System::Guid value)=0
```

## توضیحات

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PptOptions> pptOptions = System::MakeObject<PptOptions>();

pptOptions->set_RootDirectoryClsid(System::Guid(u"64818D10-4F9B-11CF-86EA-00AA00B929E8"));

pres->Save(u"pres.ppt", Aspose::Slides::Export::SaveFormat::Ppt, pptOptions);
```

## موارد مرتبط

* کلاس [Guid](../../../system/guid/)
* کلاس [IPptOptions](../)
* فضای نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)