---
title: get_IncludeHiddenSlides()
second_title: Aspose.Slides for C++ API Referansı
description: Gizli slaytların dahil edilip edilmeyeceğini alır veya ayarlar.
type: docs
weight: 27
url: /tr/aspose.slides.export/presentationanimationsgenerator/get_includehiddenslides/
---
## PresentationAnimationsGenerator::get_IncludeHiddenSlides() const yöntemi

Gizli slaytların dahil edilip edilmemesini alır veya ayarlar.

```cpp
bool Aspose::Slides::Export::PresentationAnimationsGenerator::get_IncludeHiddenSlides() const
```

## Açıklamalar



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_IncludeHiddenSlides(false);
// ...
animationsGenerator->Run(presentation->get_Slides());
```

## İlgili

* Sınıf [PresentationAnimationsGenerator](../)
* Ad Alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)