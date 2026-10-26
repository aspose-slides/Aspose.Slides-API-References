---
title: set_RootDirectoryClsid()
second_title: Aspose.Slides för C++ API-referens
description: Representerar objektklassens GUID (CLSID) som lagras i rotkatalogsposten. Kan användas för COM-aktivering av dokumentets program. Standardvärdet är '64818D11-4F9B-11CF-86EA-00AA00B929E8' som motsvarar 'Microsoft Powerpoint.Slide.8'.
type: docs
weight: 14
url: /sv/aspose.slides.export/pptoptions/set_rootdirectoryclsid/
---
## PptOptions::set_RootDirectoryClsid(System::Guid) metod


Objektklass GUID (CLSID) som lagras i rotkatalogsposten. Kan användas för COM-aktivering av dokumentets program. Standardvärdet är '64818D11-4F9B-11CF-86EA-00AA00B929E8' som motsvarar 'Microsoft Powerpoint.Slide.8'.

```cpp
void Aspose::Slides::Export::PptOptions::set_RootDirectoryClsid(System::Guid value) override
```

## Anmärkningar



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PptOptions> pptOptions = System::MakeObject<PptOptions>();

pptOptions->set_RootDirectoryClsid(System::Guid(u"64818D10-4F9B-11CF-86EA-00AA00B929E8"));

pres->Save(u"pres.ppt", Aspose::Slides::Export::SaveFormat::Ppt, pptOptions);
```




## Se även

* Klass [Guid](../../../system/guid/)
* Klass [PptOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)