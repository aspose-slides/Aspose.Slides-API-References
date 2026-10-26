---
title: get_DetectTables()
second_title: مرجع API Aspose.Slides برای C++
description: مشخص می‌کند که آیا در هنگام وارد کردن فایل PDF جداول تشخیص داده شوند.
type: docs
weight: 1
url: /fa/aspose.slides.import/pdfimportoptions/get_detecttables/
---
## PdfImportOptions::get_DetectTables() const method


تعیین می‌کند که آیا جداول در هنگام وارد کردن فایل PDF تشخیص داده شوند.

```cpp
bool Aspose::Slides::Import::PdfImportOptions::get_DetectTables() const
```

## توضیحات


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