---
title: get_DefaultDelay()
second_title: Aspose.Slides for C++ API Referansı
description: Varsayılan gecikme süresini [ms] alır.
type: docs
weight: 1
url: /tr/aspose.slides.export/presentationanimationsgenerator/get_defaultdelay/
---
## PresentationAnimationsGenerator::get_DefaultDelay() const metodu


Varsayılan gecikme süresini [ms] alır.

```cpp
int32_t Aspose::Slides::Export::PresentationAnimationsGenerator::get_DefaultDelay() const
```

## Açıklamalar



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_DefaultDelay(1000); // 1s
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## Ayrıca bakınız

* Sınıf [PresentationAnimationsGenerator](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)