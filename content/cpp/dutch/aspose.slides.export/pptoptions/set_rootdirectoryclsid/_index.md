---
title: set_RootDirectoryClsid()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de GUID van de objectklasse (CLSID) voor die is opgeslagen in de rootdirectory-vermelding. Kan worden gebruikt voor COM-activatie van de toepassing van het document. De standaardwaarde is '64818D11-4F9B-11CF-86EA-00AA00B929E8' die overeenkomt met 'Microsoft Powerpoint.Slide.8'.
type: docs
weight: 14
url: /nl/aspose.slides.export/pptoptions/set_rootdirectoryclsid/
---
## PptOptions::set_RootDirectoryClsid(System::Guid) methode


Stelt de GUID van de objectklasse (CLSID) voor die is opgeslagen in de rootdirectory-vermelding. Kan worden gebruikt voor COM-activatie van de toepassing van het document. De standaardwaarde is '64818D11-4F9B-11CF-86EA-00AA00B929E8' die overeenkomt met 'Microsoft Powerpoint.Slide.8'.

```cpp
void Aspose::Slides::Export::PptOptions::set_RootDirectoryClsid(System::Guid value) override
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