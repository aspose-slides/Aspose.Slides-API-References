---
title: set_IncludeOleData()
second_title: Aspose.Slides C++ API Referenciája
description: Igaz, ha az összes OLE adatot a prezentációból beágyazott fájlokká konvertálja a létrehozott PDF-ben. Írja **bool**.
type: docs
weight: 469
url: /hu/aspose.slides.export/ipdfoptions/set_includeoledata/
---
## IPdfOptions::set_IncludeOleData(bool) metódus

Igaz, ha az összes OLE adatot a prezentációból beágyazott fájlokká konvertálja a létrejövő PDF-ben. Írja **bool**.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_IncludeOleData(bool value)=0
```

## Megjegyzések

Az alapértelmezett **false**. 

Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_IncludeOleData(true);
pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## Lásd még

* Osztály [IPdfOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)