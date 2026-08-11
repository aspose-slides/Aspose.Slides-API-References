---
title: set_RootDirectoryClsid()
second_title: Aspose.Slides برای C++ مرجع API
description: نمایانگر GUID کلاس شیء (CLSID) که در ورودی ریشهٔ دایرکتوری ذخیره می‌شود. می‌تواند برای فعال‌سازی COM برنامهٔ سند استفاده شود. مقدار پیش‌فرض '64818D11-4F9B-11CF-86EA-00AA00B929E8' است که به 'Microsoft Powerpoint.Slide.8' مربوط می‌شود.
type: docs
weight: 14
url: /fa/aspose.slides.export/pptoptions/set_rootdirectoryclsid/
---
## PptOptions::set_RootDirectoryClsid(System::Guid) متد


نمایانگر GUID کلاس اشیا (CLSID) که در ورودی ریشهٔ دایرکتوری ذخیره می‌شود. می‌تواند برای فعال‌سازی COM برنامهٔ سند استفاده شود. مقدار پیش‌فرض '64818D11-4F9B-11CF-86EA-00AA00B929E8' است که به 'Microsoft Powerpoint.Slide.8' مربوط می‌شود.

```cpp
void Aspose::Slides::Export::PptOptions::set_RootDirectoryClsid(System::Guid value) override
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