---
title: set_AccessPermissions()
second_title: مرجع API Aspose.Slides برای C++
description: مجموعه‌ای از پرچم‌ها را شامل می‌شود که مشخص می‌کند هنگام باز شدن سند با دسترسی کاربر، کدام مجوزهای دسترسی باید اعطا شوند. به PdfAccessPermissions مراجعه کنید.
type: docs
weight: 313
url: /fa/aspose.slides.export/pdfoptions/set_accesspermissions/
---
## PdfOptions::set_AccessPermissions(PdfAccessPermissions) متد

حاوی مجموعه‌ای از پرچم‌ها است که مشخص می‌کند کدام دسترسی‌ها هنگام باز کردن سند با دسترسی کاربر باید اعطا شوند. به [PdfAccessPermissions](../../pdfaccesspermissions/) مراجعه کنید.

```cpp
void Aspose::Slides::Export::PdfOptions::set_AccessPermissions(PdfAccessPermissions value) override
```

## توضیحات



```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## موارد مرتبط

* Enum [PdfAccessPermissions](../../pdfaccesspermissions/)
* کلاس [PdfOptions](../)
* فضای نام [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)