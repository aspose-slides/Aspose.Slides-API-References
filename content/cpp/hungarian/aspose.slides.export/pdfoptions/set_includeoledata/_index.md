---
title: set_IncludeOleData()
second_title: Aspose.Slides for C++ API referencia
description: Igaz, ha az összes OLE adatot a prezentációból beágyazott fájlokká kívánja konvertálni a létrehozott PDF-ben. Írja bool.
type: docs
weight: 469
url: /hu/aspose.slides.export/pdfoptions/set_includeoledata/
---
## PdfOptions::set_IncludeOleData(bool) metódus


Igaz, ha az összes OLE adatot a prezentációból beágyazott fájlokká kívánja konvertálni a kimeneti PDF-ben. Írja **bool**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_IncludeOleData(bool value) override
```

## Megjegyzések


Az alapértelmezett érték **false**. 

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