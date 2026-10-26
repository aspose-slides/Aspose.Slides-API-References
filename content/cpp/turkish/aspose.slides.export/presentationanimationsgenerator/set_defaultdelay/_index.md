---
title: set_DefaultDelay()
second_title: Aspose.Slides C++ API Referansı
description: Varsayılan gecikme süresini [ms] olarak ayarlar.
type: docs
weight: 14
url: /tr/aspose.slides.export/presentationanimationsgenerator/set_defaultdelay/
---
## PresentationAnimationsGenerator::set_DefaultDelay(int32_t) metod


Varsayılan gecikme süresini [ms] olarak ayarlar.

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_DefaultDelay(int32_t value)
```

## Açıklamalar



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_DefaultDelay(1000); // 1sn
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## İlgili

* Sınıf [PresentationAnimationsGenerator](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)