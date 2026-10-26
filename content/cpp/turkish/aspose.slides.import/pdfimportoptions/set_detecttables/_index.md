---
title: set_DetectTables()
second_title: Aspose.Slides for C++ API Referansı
description: PDF dosyası içe aktarılırken tabloların algılanıp algılanmayacağını belirler.
type: docs
weight: 14
url: /tr/aspose.slides.import/pdfimportoptions/set_detecttables/
---
## PdfImportOptions::set_DetectTables(bool) method


PDF dosyası içe aktarılırken tabloların algılanıp algılanmayacağını belirler.

```cpp
void Aspose::Slides::Import::PdfImportOptions::set_DetectTables(bool value)
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
* Ad alanı [Aspose::Slides::Import](../../)
* Kütüphane [Aspose.Slides](../../../)