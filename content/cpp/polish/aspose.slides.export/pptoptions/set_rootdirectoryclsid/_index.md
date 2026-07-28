---
title: set_RootDirectoryClsid()
second_title: Aspose.Slides dla C++ – Referencja API
description: Reprezentuje identyfikator klasy obiektu GUID (CLSID) przechowywany w wpisie katalogu głównego. Może być używany do aktywacji COM aplikacji dokumentu. Domyślna wartość to '64818D11-4F9B-11CF-86EA-00AA00B929E8', która odpowiada 'Microsoft Powerpoint.Slide.8'.
type: docs
weight: 14
url: /pl/aspose.slides.export/pptoptions/set_rootdirectoryclsid/
---
## PptOptions::set_RootDirectoryClsid(System::Guid) metoda

Reprezentuje identyfikator klasy obiektu GUID (CLSID), który jest przechowywany w wpisie katalogu głównego. Może być używany do aktywacji COM aplikacji dokumentu. Domyślna wartość to '64818D11-4F9B-11CF-86EA-00AA00B929E8', która odpowiada 'Microsoft Powerpoint.Slide.8'.

```cpp
void Aspose::Slides::Export::PptOptions::set_RootDirectoryClsid(System::Guid value) override
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