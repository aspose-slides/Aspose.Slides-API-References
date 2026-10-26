---
title: set_IncludeHiddenSlides()
second_title: Aspose.Slides for C++ API Referansı
description: Gizli slaytların dahil edilip edilmemesini alır veya ayarlar.
type: docs
weight: 40
url: /tr/aspose.slides.export/presentationanimationsgenerator/set_includehiddenslides/
---
## PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool) metot


Gizli slaytların dahil edilip edilmeyeceğini alır veya ayarlar.

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool value)
```

## Açıklamalar



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_IncludeHiddenSlides(false);
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## Ayrıca Bakınız

* Sınıf [PresentationAnimationsGenerator](../)
* İsim Uzayı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)