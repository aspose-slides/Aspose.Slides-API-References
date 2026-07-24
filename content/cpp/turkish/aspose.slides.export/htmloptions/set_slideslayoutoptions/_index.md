---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API Referansı
description: Sunumu dışa aktarırken slaytların sayfaya yerleştirildiği modu ayarlar ISlidesLayoutOptions.
type: docs
weight: 14
url: /tr/aspose.slides.export/htmloptions/set_slideslayoutoptions/
---
## HtmlOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) metod

Sunumu dışa aktarırken slaytların sayfaya yerleştirildiği modu ayarlar [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
void Aspose::Slides::Export::HtmlOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value) override
```

## Açıklamalar

Örnek:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.html", SaveFormat::Html, options);
```

## Diğer Bağlantılar

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Sınıf [HtmlOptions](../)
* Ad Alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)