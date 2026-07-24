---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API Referansı
description: Bir sunumu dışa aktarırken slaytların sayfaya yerleştirildiği modu alır ISlidesLayoutOptions.
type: docs
weight: 157
url: /tr/aspose.slides.export/itiffoptions/get_slideslayoutoptions/
---
## ITiffOptions::get_SlidesLayoutOptions() metodu


Sunumu dışa aktarırken slaytların sayfaya yerleştirildiği modu alır [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::ITiffOptions::get_SlidesLayoutOptions()=0
```

## Açıklamalar


Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<TiffOptions> options = System::MakeObject<TiffOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.tiff", SaveFormat::Tiff, options);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Sınıf [ITiffOptions](../)
* Ad Alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)