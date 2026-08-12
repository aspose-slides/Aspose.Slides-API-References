---
title: get_DetectTables()
second_title: Aspose.Slides के लिए C++ API Reference
description: जाँचता है कि pdf फ़ाइल आयात करते समय तालिकाओं का पता लगाया जाए या नहीं।
type: docs
weight: 1
url: /hi/aspose.slides.import/pdfimportoptions/get_detecttables/
---
## PdfImportOptions::get_DetectTables() const विधि

Determines whether detect tables when importing pdf file.

```cpp
bool Aspose::Slides::Import::PdfImportOptions::get_DetectTables() const
```

## टिप्पणियाँ

Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<System::IO::Stream> stream = System::MakeObject<System::IO::FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(stream, options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## संबंधित देखें

* क्लास [PdfImportOptions](../)
* नेमस्पेस [Aspose::Slides::Import](../../)
* लाइब्रेरी [Aspose.Slides](../../../)