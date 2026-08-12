---
title: set_DetectTables()
second_title: Aspose.Slides for C++ API संदर्भ
description: pdf फ़ाइल आयात करने पर तालिकाओं का पता लगाने की आवश्यकता निर्धारित करता है।
type: docs
weight: 14
url: /hi/aspose.slides.import/pdfimportoptions/set_detecttables/
---
## PdfImportOptions::set_DetectTables(bool) मेथड


जब pdf फ़ाइल आयात करने पर तालिकाओं का पता लगाने की आवश्यकता निर्धारित करता है।

```cpp
void Aspose::Slides::Import::PdfImportOptions::set_DetectTables(bool value)
```

## टिप्पणियाँ


उदाहरण: 
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