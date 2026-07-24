---
title: get_RootDirectoryClsid()
second_title: Aspose.Slides için C++ API Referansı
description: Temel dizin girişinde depolanan nesne sınıfı GUID (CLSID) temsil eder. Belgenin uygulamasının COM aktivasyonu için kullanılabilir. Varsayılan değer, '64818D11-4F9B-11CF-86EA-00AA00B929E8' olup 'Microsoft Powerpoint.Slide.8' ile eşleşir.
type: docs
weight: 1
url: /tr/aspose.slides.export/ipptoptions/get_rootdirectoryclsid/
---
## IPptOptions::get_RootDirectoryClsid() metodu


Kök dizin girişinde depolanan nesne sınıfı GUID'sini (CLSID) temsil eder. Belgenin uygulamasının COM aktivasyonu için kullanılabilir. Varsayılan değer, 'Microsoft Powerpoint.Slide.8' ile eşleşen '64818D11-4F9B-11CF-86EA-00AA00B929E8' değeridir.

```cpp
virtual System::Guid Aspose::Slides::Export::IPptOptions::get_RootDirectoryClsid()=0
```

## Açıklamalar


```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PptOptions> pptOptions = System::MakeObject<PptOptions>();

pptOptions->set_RootDirectoryClsid(System::Guid(u"64818D10-4F9B-11CF-86EA-00AA00B929E8"));

pres->Save(u"pres.ppt", Aspose::Slides::Export::SaveFormat::Ppt, pptOptions);
```


## Diğer Bilgiler

* Sınıf [Guid](../../../system/guid/)
* Sınıf [IPptOptions](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)