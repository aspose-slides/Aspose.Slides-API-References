---
title: get_RootDirectoryClsid()
second_title: Aspose.Slides för C++ API-referens
description: Representerar objektklassens GUID (CLSID) som lagras i rotkatalogens post. Kan användas för COM-aktivering av dokumentets applikation. Standardvärdet är '64818D11-4F9B-11CF-86EA-00AA00B929E8' som motsvarar 'Microsoft Powerpoint.Slide.8'.
type: docs
weight: 1
url: /sv/aspose.slides.export/ipptoptions/get_rootdirectoryclsid/
---
## IPptOptions::get_RootDirectoryClsid() metod

Representerar objektklassens GUID (CLSID) som lagras i rotkatalogens post. Kan användas för COM-aktivering av dokumentets applikation. Standardvärdet är '64818D11-4F9B-11CF-86EA-00AA00B929E8' som motsvarar 'Microsoft Powerpoint.Slide.8'.

```cpp
virtual System::Guid Aspose::Slides::Export::IPptOptions::get_RootDirectoryClsid()=0
```

## Anmärkningar



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PptOptions> pptOptions = System::MakeObject<PptOptions>();

pptOptions->set_RootDirectoryClsid(System::Guid(u"64818D10-4F9B-11CF-86EA-00AA00B929E8"));

pres->Save(u"pres.ppt", Aspose::Slides::Export::SaveFormat::Ppt, pptOptions);
```




## Se också

* Klass [Guid](../../../system/guid/)
* Klass [IPptOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)