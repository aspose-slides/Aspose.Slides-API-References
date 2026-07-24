---
title: get_PrintFrameSlide()
second_title: Aspose.Slides için C++ API Referansı
description: Görüntülenen slaytların etrafına çerçeveler çizilip çizilmeyeceğini belirtir.
type: docs
weight: 53
url: /tr/aspose.slides.export/handoutlayoutingoptions/get_printframeslide/
---
## HandoutLayoutingOptions::get_PrintFrameSlide() const yöntemi


Görüntülenen slaytların etrafına çerçeveler çizilip çizilmeyeceğini belirtir.

```cpp
bool Aspose::Slides::Export::HandoutLayoutingOptions::get_PrintFrameSlide() const
```

## Açıklamalar


Varsayılan değer **true**'dür. 

Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);
handoutLayoutingOptions->set_PrintFrameSlide(false);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## Ayrıca Bakınız

* Sınıf [HandoutLayoutingOptions](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kitaplık [Aspose.Slides](../../../)