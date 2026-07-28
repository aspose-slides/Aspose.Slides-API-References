---
title: get_IncludeOleData()
second_title: Aspose.Slides C++ API Referencia
description: Igaz, ha az összes OLE adatot a bemutatóból beágyazott fájlokká konvertálja a létrehozott PDF-ben. Olvasás bool.
type: docs
weight: 456
url: /hu/aspose.slides.export/pdfoptions/get_includeoledata/
---
## PdfOptions::get_IncludeOleData() method

Igaz, ha az összes OLE adatot a bemutatóból beágyazott fájlokká konvertálja a létrehozott PDF-ben. Olvasás **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_IncludeOleData() override
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

* Osztály [PdfOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)