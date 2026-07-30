---
title: get_RootDirectoryClsid()
second_title: Aspose.Slides pro C++ API Reference
description: Představuje GUID (CLSID) třídy objektu, který je uložen v záznamu kořenového adresáře. Lze jej použít pro COM aktivaci aplikace dokumentu. Výchozí hodnota je '64818D11-4F9B-11CF-86EA-00AA00B929E8', která odpovídá 'Microsoft Powerpoint.Slide.8'.
type: docs
weight: 1
url: /cs/aspose.slides.export/pptoptions/get_rootdirectoryclsid/
---
## PptOptions::get_RootDirectoryClsid() metoda


Představuje GUID (CLSID) třídy objektu, který je uložen v záznamu kořenového adresáře. Lze jej použít pro COM aktivaci aplikace dokumentu. Výchozí hodnota je '64818D11-4F9B-11CF-86EA-00AA00B929E8' která odpovídá 'Microsoft Powerpoint.Slide.8'.

```cpp
System::Guid Aspose::Slides::Export::PptOptions::get_RootDirectoryClsid() override
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
* Třída [PptOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)