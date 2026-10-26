---
title: get_IncludeOleData()
second_title: Aspose.Slides för C++ API-referens
description: Sant för att konvertera all OLE-data från presentationen till inbäddade filer i den resulterande PDF-filen. Läs bool.
type: docs
weight: 456
url: /sv/aspose.slides.export/pdfoptions/get_includeoledata/
---
## PdfOptions::get_IncludeOleData() metod


Sant för att konvertera all OLE-data från presentationen till inbäddade filer i den resulterande PDF-filen. Läs **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_IncludeOleData() override
```

## Anmärkningar


Standardvärdet är **false**. 

Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_IncludeOleData(true);
pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## Se även

* Klass [PdfOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)