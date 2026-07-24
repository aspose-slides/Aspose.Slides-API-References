---
title: set_RootDirectoryClsid()
second_title: Aspose.Slides for C++ API Referansı
description: Kök dizin girişinde depolanan nesne sınıfı GUID (CLSID) temsil eder. Belgenin uygulamasının COM aktivasyonu için kullanılabilir. Varsayılan değer '64818D11-4F9B-11CF-86EA-00AA00B929E8' olup 'Microsoft Powerpoint.Slide.8' ile eşleşir.
type: docs
weight: 14
url: /tr/aspose.slides.export/ipptoptions/set_rootdirectoryclsid/
---
## IPptOptions::set_RootDirectoryClsid(System::Guid) metodu

Kök dizin girişinde depolanan nesne sınıfı GUID (CLSID) temsil eder. Belgenin uygulamasının COM aktivasyonu için kullanılabilir. Varsayılan değer '64818D11-4F9B-11CF-86EA-00AA00B929E8' olup 'Microsoft Powerpoint.Slide.8' ile eşleşir.

```cpp
virtual void Aspose::Slides::Export::IPptOptions::set_RootDirectoryClsid(System::Guid value)=0
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
* Sınıf [IPptOptions](../)
* Ad Alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)