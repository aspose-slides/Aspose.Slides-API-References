---
title: set_DetectTables()
second_title: مرجع API Aspose.Slides برای C++
description: مشخص می‌کند که آیا جداول هنگام وارد کردن فایل PDF شناسایی شوند یا خیر.
type: docs
weight: 14
url: /fa/aspose.slides.import/pdfimportoptions/set_detecttables/
---
## PdfImportOptions::set_DetectTables(bool) متد

مشخص می‌کند که آیا هنگام وارد کردن فایل PDF جداول شناسایی شوند یا نه.

```cpp
void Aspose::Slides::Import::PdfImportOptions::set_DetectTables(bool value)
```

## ملاحظات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<System::IO::Stream> stream = System::MakeObject<System::IO::FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(stream, options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* کلاس [PdfImportOptions](../)
* فضای‌نام [Aspose::Slides::Import](../../)
* کتابخانه [Aspose.Slides](../../../)