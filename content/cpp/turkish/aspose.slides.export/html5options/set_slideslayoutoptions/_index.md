---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API Referansı
description: Bir sunumu dışa aktarırken slaytların sayfaya yerleştirildiği modu ISlidesLayoutOptions ayarlar.
type: docs
weight: 170
url: /tr/aspose.slides.export/html5options/set_slideslayoutoptions/
---
## Html5Options::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) metot

Sunumu dışa aktarırken slaytların sayfaya yerleştirildiği modu ayarlar [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
void Aspose::Slides::Export::Html5Options::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value) override
```

## Açıklamalar

Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> slidesLayoutOptions = System::MakeObject<HandoutLayoutingOptions>();
slidesLayoutOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.html", SaveFormat::Html5, options);
```

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Sınıf [Html5Options](../)
* Ad Alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)