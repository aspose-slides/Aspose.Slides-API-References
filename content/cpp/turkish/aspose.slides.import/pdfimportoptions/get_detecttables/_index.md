---
title: get_DetectTables()
second_title: Aspose.Slides C++ için API Referansı
description: PDF dosyası içe aktarılırken tabloların algılanıp algılanmayacağını belirler.
type: docs
weight: 1
url: /tr/aspose.slides.import/pdfimportoptions/get_detecttables/
---
## PdfImportOptions::get_DetectTables() const metot


PDF dosyası içe aktarılırken tabloların algılanıp algılanmayacağını belirler.

```cpp
bool Aspose::Slides::Import::PdfImportOptions::get_DetectTables() const
```

## Açıklamalar


Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<System::IO::Stream> stream = System::MakeObject<System::IO::FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(stream, options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## Ayrıca Bakınız

* Sınıf [PdfImportOptions](../)
* İsim Alanı [Aspose::Slides::Import](../../)
* Kütüphane [Aspose.Slides](../../../)