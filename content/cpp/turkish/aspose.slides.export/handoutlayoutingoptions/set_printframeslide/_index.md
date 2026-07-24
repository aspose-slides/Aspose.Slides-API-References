---
title: set_PrintFrameSlide()
second_title: Aspose.Slides for C++ API Referansı
description: Görüntülenen slaytların etrafına çerçeve çizilip çizilmeyeceğini belirtir.
type: docs
weight: 66
url: /tr/aspose.slides.export/handoutlayoutingoptions/set_printframeslide/
---
## HandoutLayoutingOptions::set_PrintFrameSlide(bool) metod

Görüntülenen slaytların etrafına çerçeveler çizilip çizilmeyeceğini belirtir.

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_PrintFrameSlide(bool value)
```

## Açıklamalar

Varsayılan değer **true**'dır. 

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

## İlgili

* Sınıf [HandoutLayoutingOptions](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)