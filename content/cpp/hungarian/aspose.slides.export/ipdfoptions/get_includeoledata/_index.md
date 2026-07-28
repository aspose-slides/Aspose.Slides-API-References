---
title: get_IncludeOleData()
second_title: Aspose.Slides a C++-hoz API referenciája
description: Igaz, ha minden OLE adatot a prezentációból beágyazott fájlokká kell konvertálni a létrehozott PDF-ben. Olvasás bool.
type: docs
weight: 456
url: /hu/aspose.slides.export/ipdfoptions/get_includeoledata/
---
## IPdfOptions::get_IncludeOleData() metódus


Igaz a teljes OLE adat átalakításához a prezentációból beágyazott fájlokká a létrehozott PDF-ben. Olvasás **bool**.

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_IncludeOleData()=0
```

## Megjegyzés


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