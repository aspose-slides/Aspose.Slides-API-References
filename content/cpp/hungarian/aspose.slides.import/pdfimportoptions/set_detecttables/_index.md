---
title: set_DetectTables()
second_title: Aspose.Slides C++ API referencia
description: Megállapítja, hogy a PDF-fájl importálásakor táblázatot detektáljon-e.
type: docs
weight: 14
url: /hu/aspose.slides.import/pdfimportoptions/set_detecttables/
---
## PdfImportOptions::set_DetectTables(bool) metódus


Megállapítja, hogy a táblázatok detektálása be legyen-e kapcsolva PDF-fájl importálásakor.

```cpp
void Aspose::Slides::Import::PdfImportOptions::set_DetectTables(bool value)
```

## Megjegyzések


Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<System::IO::Stream> stream = System::MakeObject<System::IO::FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(stream, options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## Lásd még

* Osztály [PdfImportOptions](../)
* Névterület [Aspose::Slides::Import](../../)
* Könyvtár [Aspose.Slides](../../../)