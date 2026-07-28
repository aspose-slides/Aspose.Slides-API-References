---
title: set_RootDirectoryClsid()
second_title: Aspose.Slides C++ API-referencia
description: Az objektum osztály GUID (CLSID) képviseli, amely a gyökérkönyvtár bejegyzésben van tárolva. A dokumentum alkalmazásának COM aktiválásához használható. Az alapértelmezett érték a '64818D11-4F9B-11CF-86EA-00AA00B929E8', amely a 'Microsoft Powerpoint.Slide.8'-nak felel meg.
type: docs
weight: 14
url: /hu/aspose.slides.export/ipptoptions/set_rootdirectoryclsid/
---
## IPptOptions::set_RootDirectoryClsid(System::Guid) metódus


Az objektum osztály GUID (CLSID) jelöli, amely a gyökérkönyvtár bejegyzésben van tárolva. A dokumentum alkalmazásának COM aktiválásához használható. Az alapértelmezett érték a '64818D11-4F9B-11CF-86EA-00AA00B929E8', amely a 'Microsoft Powerpoint.Slide.8'-nak felel meg.

```cpp
virtual void Aspose::Slides::Export::IPptOptions::set_RootDirectoryClsid(System::Guid value)=0
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
* Osztály [IPptOptions](../)
* Névterület [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)