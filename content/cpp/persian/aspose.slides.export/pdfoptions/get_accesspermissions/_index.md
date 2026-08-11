---
title: get_AccessPermissions()
second_title: مرجع API Aspose.Slides برای C++
description: حاوی مجموعه‌ای از پرچم‌ها است که مشخص می‌کند هنگام باز شدن سند با دسترسی کاربر، چه مجوزهای دسترسی باید اعطا شوند. ببینید PdfAccessPermissions.
type: docs
weight: 300
url: /fa/aspose.slides.export/pdfoptions/get_accesspermissions/
---
## PdfOptions::get_AccessPermissions() متد

یک مجموعه از پرچم‌ها را شامل می‌شود که مشخص می‌کند هنگام باز شدن سند با دسترسی کاربر، چه مجوزهایی باید اعطا شود. ببینید [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
PdfAccessPermissions Aspose::Slides::Export::PdfOptions::get_AccessPermissions() override
```

## توضیحات

```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## مراجع مرتبط

* Enum [PdfAccessPermissions](../../pdfaccesspermissions/)
* کلاس [PdfOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)