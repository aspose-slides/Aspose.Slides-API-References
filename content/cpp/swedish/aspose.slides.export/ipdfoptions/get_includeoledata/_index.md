---
title: get_IncludeOleData()
second_title: Aspose.Slides för C++ API-referens
description: Sant för att konvertera all OLE-data från presentationen till inbäddade filer i den resulterande PDF. Läs bool.
type: docs
weight: 456
url: /sv/aspose.slides.export/ipdfoptions/get_includeoledata/
---
## IPdfOptions::get_IncludeOleData() metod


Sant för att konvertera all OLE data från presentationen till inbäddade filer i den resulterande PDF. Läs **bool**.

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_IncludeOleData()=0
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

## Se också

* Klass [IPdfOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)