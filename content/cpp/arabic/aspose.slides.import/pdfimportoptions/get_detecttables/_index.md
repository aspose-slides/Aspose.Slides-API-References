---
title: get_DetectTables()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتحديد ما إذا كان يتم اكتشاف الجداول عند استيراد ملف PDF.
type: docs
weight: 1
url: /ar/aspose.slides.import/pdfimportoptions/get_detecttables/
---
## PdfImportOptions::get_DetectTables() const طريقة

يحدد ما إذا كان يتم اكتشاف الجداول عند استيراد ملف PDF.

```cpp
bool Aspose::Slides::Import::PdfImportOptions::get_DetectTables() const
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

## انظر أيضًا

* الفئة [PdfImportOptions](../)
* النطاق [Aspose::Slides::Import](../../)
* المكتبة [Aspose.Slides](../../../)