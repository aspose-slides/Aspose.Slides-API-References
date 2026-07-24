---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API Referansı
description: Sunumu dışa aktarırken slaytların sayfaya yerleştirildiği modu ISlidesLayoutOptions ayarlar.
type: docs
weight: 378
url: /tr/aspose.slides.export/ipdfoptions/set_slideslayoutoptions/
---
## IPdfOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) metod


Sunumu dışa aktarırken slaytların sayfaya yerleştirildiği modu ayarlar [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value)=0
```

## Açıklamalar


Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Sınıf [IPdfOptions](../)
* İsim Uzayı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)