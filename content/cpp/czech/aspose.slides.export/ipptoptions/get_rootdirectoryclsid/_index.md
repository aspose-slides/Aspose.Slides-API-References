---
title: get_RootDirectoryClsid()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Representuje GUID třídy objektu (CLSID), který je uložen v záznamu kořenového adresáře. Lze jej použít k aktivaci COM aplikace dokumentu. Výchozí hodnota je '64818D11-4F9B-11CF-86EA-00AA00B929E8', která odpovídá 'Microsoft Powerpoint.Slide.8'.
type: docs
weight: 1
url: /cs/aspose.slides.export/ipptoptions/get_rootdirectoryclsid/
---
## IPptOptions::get_RootDirectoryClsid() metoda


Representuje GUID třídy objektu (CLSID), který je uložen v záznamu kořenového adresáře. Lze jej použít k aktivaci COM aplikace dokumentu. Výchozí hodnota je '64818D11-4F9B-11CF-86EA-00AA00B929E8', která odpovídá 'Microsoft Powerpoint.Slide.8'.

```cpp
virtual System::Guid Aspose::Slides::Export::IPptOptions::get_RootDirectoryClsid()=0
```

## Poznámky



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PptOptions> pptOptions = System::MakeObject<PptOptions>();

pptOptions->set_RootDirectoryClsid(System::Guid(u"64818D10-4F9B-11CF-86EA-00AA00B929E8"));

pres->Save(u"pres.ppt", Aspose::Slides::Export::SaveFormat::Ppt, pptOptions);
```




## Viz také

* Třída [Guid](../../../system/guid/)
* Třída [IPptOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)