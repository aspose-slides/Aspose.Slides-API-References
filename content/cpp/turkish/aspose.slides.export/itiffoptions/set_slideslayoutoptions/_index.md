---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API Referansı
description: Sunumu dışa aktarırken slaytların sayfaya yerleştirildiği modu ISlidesLayoutOptions ayarlar.
type: docs
weight: 170
url: /tr/aspose.slides.export/itiffoptions/set_slideslayoutoptions/
---
## ITiffOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) metodu

Sunumu dışa aktarırken slaytların sayfaya yerleştirildiği modu ayarlar [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual void Aspose::Slides::Export::ITiffOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value)=0
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