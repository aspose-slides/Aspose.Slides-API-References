---
title: get_RootDirectoryClsid()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de objectklasse GUID (CLSID) voor die is opgeslagen in de root directory entry. Kan worden gebruikt voor COM-activatie van de applicatie van het document. De standaardwaarde is '64818D11-4F9B-11CF-86EA-00AA00B929E8' die overeenkomt met 'Microsoft Powerpoint.Slide.8'.
type: docs
weight: 1
url: /nl/aspose.slides.export/pptoptions/get_rootdirectoryclsid/
---
## PptOptions::get_RootDirectoryClsid() methode

Vertegenwoordigt de objectklasse GUID (CLSID) die is opgeslagen in de root directory entry. Kan worden gebruikt voor COM-activatie van de applicatie van het document. De standaardwaarde is '64818D11-4F9B-11CF-86EA-00AA00B929E8' die overeenkomt met 'Microsoft Powerpoint.Slide.8'.

```cpp
System::Guid Aspose::Slides::Export::PptOptions::get_RootDirectoryClsid() override
```

## Opmerkingen



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PptOptions> pptOptions = System::MakeObject<PptOptions>();

pptOptions->set_RootDirectoryClsid(System::Guid(u"64818D10-4F9B-11CF-86EA-00AA00B929E8"));

pres->Save(u"pres.ppt", Aspose::Slides::Export::SaveFormat::Ppt, pptOptions);
```




## Zie ook

* Klasse [Guid](../../../system/guid/)
* Klasse [PptOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)