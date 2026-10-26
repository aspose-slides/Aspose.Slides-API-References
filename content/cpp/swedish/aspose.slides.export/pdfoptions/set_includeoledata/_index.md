---
title: set_IncludeOleData()
second_title: Aspose.Slides för C++ API-referens
description: Sant för att konvertera all OLE-data från presentationen till inbäddade filer i den resulterande PDF-filen. Skriv bool.
type: docs
weight: 469
url: /sv/aspose.slides.export/pdfoptions/set_includeoledata/
---
## PdfOptions::set_IncludeOleData(bool) metod


Sant för att konvertera all OLE-data från presentationen till inbäddade filer i den resulterande PDF-filen. Skriv **bool**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_IncludeOleData(bool value) override
```

## Anmärkningar


Standard är **false**. 

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