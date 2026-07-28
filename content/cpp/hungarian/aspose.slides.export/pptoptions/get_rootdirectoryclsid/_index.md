---
title: get_RootDirectoryClsid()
second_title: Aspose.Slides C++ API-referencia
description: Az objektum osztály GUID-ját (CLSID) képviseli, amely a gyökérkönyvtár bejegyzésben van tárolva. A dokumentum alkalmazásának COM aktiválásához használható. Az alapértelmezett érték '64818D11-4F9B-11CF-86EA-00AA00B929E8', amely a 'Microsoft Powerpoint.Slide.8'-nek felel meg.
type: docs
weight: 1
url: /hu/aspose.slides.export/pptoptions/get_rootdirectoryclsid/
---
## PptOptions::get_RootDirectoryClsid() metódus

Az objektum osztály GUID-ját (CLSID) képviseli, amely a gyökérkönyvtár bejegyzésben van tárolva. COM aktiváláshoz használható a dokumentum alkalmazásához. Alapértelmezett érték a '64818D11-4F9B-11CF-86EA-00AA00B929E8' amely a 'Microsoft Powerpoint.Slide.8'-nek felel meg.

```cpp
System::Guid Aspose::Slides::Export::PptOptions::get_RootDirectoryClsid() override
```

## Megjegyzések



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PptOptions> pptOptions = System::MakeObject<PptOptions>();

pptOptions->set_RootDirectoryClsid(System::Guid(u"64818D10-4F9B-11CF-86EA-00AA00B929E8"));

pres->Save(u"pres.ppt", Aspose::Slides::Export::SaveFormat::Ppt, pptOptions);
```




## Lásd még

* Osztály [Guid](../../../system/guid/)
* Osztály [PptOptions](../)
* Névterület [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)