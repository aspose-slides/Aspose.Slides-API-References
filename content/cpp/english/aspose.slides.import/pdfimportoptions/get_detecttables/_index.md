---
title: get_DetectTables()
second_title: Aspose.Slides for C++ API Reference
description: Determines whether detect tables when importing pdf file.
type: docs
weight: 1
url: /aspose.slides.import/pdfimportoptions/get_detecttables/
---
## PdfImportOptions::get_DetectTables() const method


Determines whether detect tables when importing pdf file.

```cpp
bool Aspose::Slides::Import::PdfImportOptions::get_DetectTables() const
```

## Remarks


Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<System::IO::Stream> stream = System::MakeObject<System::IO::FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(stream, options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## See Also

* Class [PdfImportOptions](../)
* Namespace [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)