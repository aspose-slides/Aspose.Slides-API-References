---
title: get_AccessPermissions()
second_title: Aspose.Slides برای C++ مرجع API
description: مجموعه‌ای از پرچم‌ها را شامل می‌شود که مشخص می‌کند چه مجوزهای دسترسی‌ای هنگام باز شدن سند با دسترسی کاربر باید اعطا شود. به PdfAccessPermissions مراجعه کنید.
type: docs
weight: 261
url: /fa/aspose.slides.export/ipdfoptions/get_accesspermissions/
---
## IPdfOptions::get_AccessPermissions() متد

مجموعه‌ای از پرچم‌ها را شامل می‌شود که مشخص می‌کند چه مجوزهای دسترسی‌ای هنگام باز شدن سند با دسترسی کاربر باید اعطا شود. به [PdfAccessPermissions](../../pdfaccesspermissions/) مراجعه کنید.

```cpp
virtual PdfAccessPermissions Aspose::Slides::Export::IPdfOptions::get_AccessPermissions()=0
```

## ملاحظات

```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## مراجع مرتبط

* enum [PdfAccessPermissions](../../pdfaccesspermissions/)
* کلاس [IPdfOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)