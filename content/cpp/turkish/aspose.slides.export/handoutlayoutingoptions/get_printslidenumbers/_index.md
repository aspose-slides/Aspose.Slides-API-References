---
title: get_PrintSlideNumbers()
second_title: Aspose.Slides için C++ API Referansı
description: Görüntülenen slayt numaralarının yazdırılıp yazdırılmayacağını belirtir.
type: docs
weight: 27
url: /tr/aspose.slides.export/handoutlayoutingoptions/get_printslidenumbers/
---
## HandoutLayoutingOptions::get_PrintSlideNumbers() const metod

Görüntülenen slayt numaralarının yazdırılıp yazdırılmayacağını belirtir.

```cpp
bool Aspose::Slides::Export::HandoutLayoutingOptions::get_PrintSlideNumbers() const
```

## Açıklamalar

Varsayılan değer **true**'dur.

Örnek:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);
handoutLayoutingOptions->set_PrintSlideNumbers(false);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## Diğer Bağlantılar

* Sınıf [HandoutLayoutingOptions](../)
* İsim Uzayı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)