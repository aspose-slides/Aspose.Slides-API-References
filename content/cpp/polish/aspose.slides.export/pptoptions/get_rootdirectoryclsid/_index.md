---
title: get_RootDirectoryClsid()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Reprezentuje identyfikator GUID klasy obiektu (CLSID) przechowywany w wpisie katalogu głównego. Może być używany do aktywacji COM aplikacji dokumentu. Domyślna wartość to '64818D11-4F9B-11CF-86EA-00AA00B929E8', która odpowiada 'Microsoft Powerpoint.Slide.8'.
type: docs
weight: 1
url: /pl/aspose.slides.export/pptoptions/get_rootdirectoryclsid/
---
## PptOptions::get_RootDirectoryClsid() metoda

Reprezentuje identyfikator GUID klasy obiektu (CLSID) przechowywany w wpisie katalogu głównego. Może być używany do aktywacji COM aplikacji dokumentu. Domyślna wartość to '64818D11-4F9B-11CF-86EA-00AA00B929E8', która odpowiada 'Microsoft Powerpoint.Slide.8'.

```cpp
System::Guid Aspose::Slides::Export::PptOptions::get_RootDirectoryClsid() override
```

## Uwagi



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PptOptions> pptOptions = System::MakeObject<PptOptions>();

pptOptions->set_RootDirectoryClsid(System::Guid(u"64818D10-4F9B-11CF-86EA-00AA00B929E8"));

pres->Save(u"pres.ppt", Aspose::Slides::Export::SaveFormat::Ppt, pptOptions);
```


## Zobacz także

* Klasa [Guid](../../../system/guid/)
* Klasa [PptOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)