---
title: set_RootDirectoryClsid()
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt die Objektklassen-GUID (CLSID) dar, die im Root-Verzeichnis-Eintrag gespeichert ist. Kann für die COM-Aktivierung der Anwendung des Dokuments verwendet werden. Der Standardwert ist '64818D11-4F9B-11CF-86EA-00AA00B929E8', der 'Microsoft Powerpoint.Slide.8' entspricht.
type: docs
weight: 14
url: /de/aspose.slides.export/ipptoptions/set_rootdirectoryclsid/
---
## IPptOptions::set_RootDirectoryClsid(System::Guid) Methode


Stellt die Objektklassen-GUID (CLSID) dar, die im Root-Verzeichnis-Eintrag gespeichert ist. Kann für die COM-Aktivierung der Anwendung des Dokuments verwendet werden. Der Standardwert ist '64818D11-4F9B-11CF-86EA-00AA00B929E8', der 'Microsoft Powerpoint.Slide.8' entspricht.

```cpp
virtual void Aspose::Slides::Export::IPptOptions::set_RootDirectoryClsid(System::Guid value)=0
```

## Hinweise



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PptOptions> pptOptions = System::MakeObject<PptOptions>();

pptOptions->set_RootDirectoryClsid(System::Guid(u"64818D10-4F9B-11CF-86EA-00AA00B929E8"));

pres->Save(u"pres.ppt", Aspose::Slides::Export::SaveFormat::Ppt, pptOptions);
```




## Siehe auch

* Klasse [Guid](../../../system/guid/)
* Klasse [IPptOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)