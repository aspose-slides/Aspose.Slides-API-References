---
title: get_RootDirectoryClsid()
second_title: Aspose.Slides for C++ API Referansı
description: Kök dizin girişinde depolanan nesne sınıfı GUID'sini (CLSID) temsil eder. Belgenin uygulamasının COM etkinleştirmesi için kullanılabilir. Varsayılan değer '64818D11-4F9B-11CF-86EA-00AA00B929E8' olup 'Microsoft Powerpoint.Slide.8' ile eşleşir.
type: docs
weight: 1
url: /tr/aspose.slides.export/pptoptions/get_rootdirectoryclsid/
---
## PptOptions::get_RootDirectoryClsid() metodu


Kök dizin girişinde depolanan nesne sınıfı GUID'sini (CLSID) temsil eder. Belgenin uygulamasının COM etkinleştirmesi için kullanılabilir. Varsayılan değer '64818D11-4F9B-11CF-86EA-00AA00B929E8' olup 'Microsoft Powerpoint.Slide.8' ile eşleşir.

```cpp
System::Guid Aspose::Slides::Export::PptOptions::get_RootDirectoryClsid() override
```

## Açıklamalar



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PptOptions> pptOptions = System::MakeObject<PptOptions>();

pptOptions->set_RootDirectoryClsid(System::Guid(u"64818D10-4F9B-11CF-86EA-00AA00B929E8"));

pres->Save(u"pres.ppt", Aspose::Slides::Export::SaveFormat::Ppt, pptOptions);
```




## Ayrıca Bakınız

* Sınıf [Guid](../../../system/guid/)
* Sınıf [PptOptions](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)