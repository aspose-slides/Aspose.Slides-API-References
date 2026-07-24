---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API Referansı
description: Sunumu dışa aktarırken slaytların sayfaya yerleştirildiği modu ayarlar ISlidesLayoutOptions.
type: docs
weight: 14
url: /tr/aspose.slides.export/pdfoptions/set_slideslayoutoptions/
---
## PdfOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) yöntemi

Sunumu dışa aktarırken slaytların sayfaya yerleştirildiği modu ayarlar [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
void Aspose::Slides::Export::PdfOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value) override
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

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Sınıf [PdfOptions](../)
* İsim Alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)