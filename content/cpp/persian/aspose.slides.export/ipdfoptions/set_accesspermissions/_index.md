---
title: set_AccessPermissions()
second_title: مرجع API Aspose.Slides برای C++
description: مجموعه‌ای از پرچم‌ها را شامل می‌شود که مشخص می‌کند هنگام باز شدن سند با دسترسی کاربر چه مجوزهای دسترسی باید اعطا شود. به PdfAccessPermissions مراجعه کنید.
type: docs
weight: 274
url: /fa/aspose.slides.export/ipdfoptions/set_accesspermissions/
---
## IPdfOptions::set_AccessPermissions(PdfAccessPermissions) متد

حاوی مجموعه‌ای از پرچم‌ها است که مشخص می‌کند هنگام باز شدن سند با دسترسی کاربر چه مجوزهای دسترسی باید اعطا شود. به [PdfAccessPermissions](../../pdfaccesspermissions/) مراجعه کنید.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_AccessPermissions(PdfAccessPermissions value)=0
```

## توضیحات



```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## همچنین ببینید

* شمارش [PdfAccessPermissions](../../pdfaccesspermissions/)
* کلاس [IPdfOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)