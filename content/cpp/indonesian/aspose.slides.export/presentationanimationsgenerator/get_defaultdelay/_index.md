---
title: get_DefaultDelay()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan waktu tunda default [ms].
type: docs
weight: 1
url: /id/aspose.slides.export/presentationanimationsgenerator/get_defaultdelay/
---
## PresentationAnimationsGenerator::get_DefaultDelay() const metode


Mendapatkan waktu tunda default [ms].

```cpp
int32_t Aspose::Slides::Export::PresentationAnimationsGenerator::get_DefaultDelay() const
```

## Keterangan



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_DefaultDelay(1000); // 1 dtk
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## Lihat Juga

* Kelas [PresentationAnimationsGenerator](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Pustaka [Aspose.Slides](../../../)