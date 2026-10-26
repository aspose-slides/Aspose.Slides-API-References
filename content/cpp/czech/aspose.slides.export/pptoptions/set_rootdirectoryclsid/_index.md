---
title: set_RootDirectoryClsid()
second_title: Reference API Aspose.Slides pro C++
description: Reprezentuje GUID třídy objektu (CLSID), který je uložen v položce kořenového adresáře. Lze jej použít pro COM aktivaci aplikace dokumentu. Výchozí hodnota je '64818D11-4F9B-11CF-86EA-00AA00B929E8', která odpovídá 'Microsoft Powerpoint.Slide.8'.
type: docs
weight: 14
url: /cs/aspose.slides.export/pptoptions/set_rootdirectoryclsid/
---
## PptOptions::set_RootDirectoryClsid(System::Guid) metoda

Representuje GUID třídy objektu (CLSID), který je uložen v kořenovém adresáři. Lze jej použít pro COM aktivaci aplikace dokumentu. Výchozí hodnota je '64818D11-4F9B-11CF-86EA-00AA00B929E8', která odpovídá 'Microsoft Powerpoint.Slide.8'.

```cpp
void Aspose::Slides::Export::PptOptions::set_RootDirectoryClsid(System::Guid value) override
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
* Library [Aspose.Slides](../../../)