---
title: set_RootDirectoryClsid()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Reprezentuje GUID klasy obiektu (CLSID) przechowywany w wpisie katalogu głównego. Może być używany do aktywacji COM aplikacji dokumentu. Domyślna wartość to '64818D11-4F9B-11CF-86EA-00AA00B929E8', która odpowiada 'Microsoft Powerpoint.Slide.8'.
type: docs
weight: 14
url: /pl/aspose.slides.export/ipptoptions/set_rootdirectoryclsid/
---
## IPptOptions::set_RootDirectoryClsid(System::Guid) metoda


Reprezentuje GUID klasy obiektu (CLSID) przechowywany w wpisie katalogu głównego. Może być używany do aktywacji COM aplikacji dokumentu. Domyślna wartość to '64818D11-4F9B-11CF-86EA-00AA00B929E8', która odpowiada 'Microsoft Powerpoint.Slide.8'.

```cpp
virtual void Aspose::Slides::Export::IPptOptions::set_RootDirectoryClsid(System::Guid value)=0
```

## Uwagi



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PptOptions> pptOptions = System::MakeObject<PptOptions>();

pptOptions->set_RootDirectoryClsid(System::Guid(u"64818D10-4F9B-11CF-86EA-00AA00B929E8"));

pres->Save(u"pres.ppt", Aspose::Slides::Export::SaveFormat::Ppt, pptOptions);
```




## Zobacz też

* Klasa [Guid](../../../system/guid/)
* Klasa [IPptOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)