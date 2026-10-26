---
title: set_Handout()
second_title: Aspose.Slides için C++ API Referansı
description: Sayfada HandoutType üzerine kaç slayt yerleştirileceğini ve hangi sırada olacağını belirtir.
type: docs
weight: 14
url: /tr/aspose.slides.export/handoutlayoutingoptions/set_handout/
---
## HandoutLayoutingOptions::set_Handout(HandoutType) metodu


Sayfada [HandoutType](../../handouttype/) üzerine yerleştirilecek slayt sayısını ve sırasını belirtir.

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_Handout(HandoutType value)
```

## Açıklamalar


Varsayılan değer **[HandoutType::Handouts6Horizontal](../../handouttype/)**'tır. 

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
* İsim Alanı [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)