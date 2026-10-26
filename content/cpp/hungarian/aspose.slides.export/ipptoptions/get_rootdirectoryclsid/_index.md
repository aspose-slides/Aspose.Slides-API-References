---
title: get_RootDirectoryClsid()
second_title: Aspose.Slides for C++ API hivatkozás
description: Az objektum osztály GUID (CLSID) képviseli, amely a gyökérkönyvtár bejegyzésben van tárolva. Használható a dokumentum alkalmazásának COM aktiválásához. Az alapértelmezett érték a '64818D11-4F9B-11CF-86EA-00AA00B929E8', amely a 'Microsoft Powerpoint.Slide.8'-re vonatkozik.
type: docs
weight: 1
url: /hu/aspose.slides.export/ipptoptions/get_rootdirectoryclsid/
---
## IPptOptions::get_RootDirectoryClsid() metódus

Az objektum osztály GUID (CLSID) képviseli, amely a gyökérkönyvtár bejegyzésben tárolódik. Használható a dokumentum alkalmazásának COM aktiválásához. Az alapértelmezett érték a '64818D11-4F9B-11CF-86EA-00AA00B929E8', amely a 'Microsoft Powerpoint.Slide.8'-re vonatkozik.

```cpp
virtual System::Guid Aspose::Slides::Export::IPptOptions::get_RootDirectoryClsid()=0
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
* Névtere [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)