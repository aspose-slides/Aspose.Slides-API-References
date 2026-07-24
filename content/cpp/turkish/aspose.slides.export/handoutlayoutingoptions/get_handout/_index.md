---
title: get_Handout()
second_title: Aspose.Slides for C++ API Referansı
description: HandoutType sayfasına kaç slayt yerleştirileceğini ve hangi sırayla konulacağını belirler.
type: docs
weight: 1
url: /tr/aspose.slides.export/handoutlayoutingoptions/get_handout/
---
## HandoutLayoutingOptions::get_Handout() const metodu

Sayfa [HandoutType](../../handouttype/) üzerine kaç slayt yerleştirileceğini ve hangi sırayla yer alacağını belirtir.

```cpp
HandoutType Aspose::Slides::Export::HandoutLayoutingOptions::get_Handout() const
```

## Açıklamalar

Varsayılan değer **[HandoutType::Handouts6Horizontal](../../handouttype/)**. 

Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## Ayrıca Bakınız

* Enum [HandoutType](../../handouttype/)
* Sınıf [HandoutLayoutingOptions](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)