---
title: set_RootDirectoryClsid()
second_title: Aspose.Slides C++ API-referencia
description: Az objektum osztály GUID-ját (CLSID) jelöli, amely a gyökérkönyvtár bejegyzésében van tárolva. Használható a dokumentum alkalmazásának COM aktiválásához. Az alapértelmezett érték a '64818D11-4F9B-11CF-86EA-00AA00B929E8', amely a 'Microsoft Powerpoint.Slide.8'-nek felel meg.
type: docs
weight: 14
url: /hu/aspose.slides.export/pptoptions/set_rootdirectoryclsid/
---
## PptOptions::set_RootDirectoryClsid(System::Guid) metódus

Az objektum osztály GUID-ját (CLSID) jelöli, amely a gyökérkönyvtár bejegyzésében van tárolva. Használható a dokumentum alkalmazásának COM aktiválásához. Az alapértelmezett érték a '64818D11-4F9B-11CF-86EA-00AA00B929E8', amely a 'Microsoft Powerpoint.Slide.8'-nek felel meg.

```cpp
void Aspose::Slides::Export::PptOptions::set_RootDirectoryClsid(System::Guid value) override
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
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)